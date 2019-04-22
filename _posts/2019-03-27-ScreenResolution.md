---
layout: post
title: Screen Resolution
subtitle: UI considerations on different resolutions
tags: [Layout]
categories: [Layout]
---

## Screen Resolution
PC and mobile devices have a variety of screen resolutions; this needs to be considered in the design of UIs for games. 

Modern console games are designed for the most popular resolutions:
- **720p HD:** 1280 x 720
- **1080p HD:** 1920 x 1080
- **4K UHD:** 3840 x 2160

![Screen Resolutions](/privatebebomalaka/img/Screen_Resolutions.jpg)  
_HD televisions maintain an aspect ratio of 16:9_

An item displayed in HD and 4K occupies the same area on the screen. This means you can use the same UI layout for both resolutions, as long as you keep the following in mind:
- **Pixel density:** For every pixel in HD, there are four pixels in 4K. This adds detail to images and crispness to fonts and thin lines. Create graphics for 4K, because scaling down to 1080p is easier than scaling up to 4K.
- **File and DPI settings:** DPI (Dots Per Inch) is the unit of resolution for print and digital files. HD televisions have a resolution of 72 dpi, and most visual components use this resolution.
- **Font size:** Standard 1080 HD fonts render out at 72 dpi. If you keep your 4K canvas at 72 dpi, your fonts will be rendered at half the size. To keep your font size consistent, change your resolution settings from 72 dpi in your 1080 files to 144 dpi in your 4K files.


{: .box-warning}
**TIP:** To check whether your designs will be legible, reduce your PC image to 33%. If you cannot read the information at 33%, then your information will be too small to read at 10 feet.

<br>


## Safe Frame
Safe Frame is a display area where text and visuals are guaranteed to be visible on all television sets. Safe Frame was standard in CRT television sets. Imperfections in manufacturing caused CRT sets to position the broadcast image inconsistently, and Safe Frame compensated for this deficiency. Safe Frame is still used for digital flat screen televisions, even though images are displayed consistently on most television sets.

Screens have two Safe Frame areas:
- **Action Safe** is where vital gameplay is rendered. This area takes up 95% of the screen’s resolution. For example, at 1920 x 1080, Action Safe is 1824 x 1026.
- **Title Safe** is where text and graphics are rendered. This area is used to position menus, titles, and HUD elements, and its dimensions are 90% of the screen resolution that is translated. For example, at 1920 x 1080, Title Safe is 1728 x 972.

When designing grids, keep everything within the Safe Frame:  
![Safe Screen](/privatebebomalaka/img/Screen_Safe.jpg)  

<br>

## Information density
The viewable screen’s size can determine the amount of information within a menu. Designing console games played at 10 feet is very different from designing PC games played at 2 feet. As the distance increases, the player’s ability to comprehend information decreases. A free-flowing mouse is much faster and accurate than a controller on a grid layout.

To help players focus on the information on the screen, use negative space, which is the area around an object or text that does not have any importance and can be used to frame information. 

Reducing the amount of information in the menus increases the player’s ability to navigate the screen and makes the information easier to comprehend.


{: .box-warning}
**Tip:** Within a menu, show only the vital information related to a selection or topic. Offer more detailed information on a separate screen or a pop-up window. This will reduce the risk of information overload for most players, who want to start playing immediately.

<br>
