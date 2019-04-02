---
layout: post
title: Raster vs Vector
subtitle: Which technique to use  
tags: [2D Artwork, Process]
categories: [2D Artwork]
---

Most games use pixel-based raster images throughout the UI because these images are easy to use and implement. However, raster images do not scale up well, so they might not be the best solution for some games.

Vector images can be easily scaled to any size, by using points and curves. Scaling does not require increasing the file size, and scaled images can be translated into polygons and other shapes:
 
![Raster Vector Polygon](/privatebebomalaka/img/ImageUse.png)  

The disadvantage of using complex vector images is a drop-in performance, which causes a drastic loss in framerate.

{: .box-warning}
We recommend that you talk to your engineers, run some performance tests with raster as well as vector images, and determine the file type that works best for your UI and game.
 
<br>
<br>
