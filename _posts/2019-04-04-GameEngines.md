---
layout: post
title: Working with Game Engines
subtitle: Areas to know before production
tags: [3D Artwork]
categories: [3DArtwork]
---

Every game will be built with a game engine: licensed, custom, or anything in between. Before designing any UI, ask your engineer or technical artist to help you understand the limitations of your engine. Determine what tech you need and how you want to exploit the system while keeping it performant. Document your decisions, and test them out regularly along the following lines:
- UI capabilities
- New tech and features
- Exploitation of the system
- Performance
- Documentation
- Collaboration
- Testing and experimentation

<br>

## Power of shaders
Use shaders to create effects for UI elements without having to render each element by hand. Run shaders through the game engine and GPU to shorten the time spent on designing and polishing multiple assets. Also use shaders to create a visual style of your game by following the identity of your brand and by keeping components and screens consistent throughout the game.

In the example that follows, we start with a base artwork: a flat image with a subtle transparency. Using shaders, you can program visual effects such as drop shadows, blur effects, and chromatic aberrations. The use of a shader helps make such a simple base artwork more dynamic and pleasing to the eye.

![Shader Examples](/privatebebo/img/Shader_Examples.jpg)  

In Crysis, the designers added a scan line and glow effects on top of the UI, to make it look like a projection:  
![Scan Line shader](/privatebebo/img/Shader_ScanLine.jpg)

To create this effect, the designers mapped the UI elements to polygons and then added the shader effects to the polygons:  
![Scan Line polygons](/privatebebo/img/Shader_ScanLine_poly.jpg)

These are the 2D elements mapped on a 3D layout. Mapping UI elements to polygons also lets you use the game engine to composite your UI within the game environments.  
![Scan Line mapping](/privatebebo/img/Shader_ScanLine_mapping.jpg)

<br>

## Screen composition
There's a lot of fun in experimenting with the composition of UI components and in-game characters and environments. Screen composition can help connect the UI to your gameplay, so take advantage of areas of the game that will help create interesting UI layout.

Finding unique camera angles and juxtaposing menus with game objects can create interesting compositions and highlight areas of the game that would be difficult to see in traditional flat 2D menus.

![Screen Composition in world](/privatebebo/img/Screen_Composition.gif)

<br>

## Scenes
To create a more immersive experience in a game, some designers will use a fixed location or a hub in the in-game world. The goal is to stage the game with preset cameras and to integrate the environment’s elements with in-game menus. 

The more immersive a menu you’re trying to design, the more effort and resources you might have to expand. It is critical that you create a prototype to spec out the camera, character and menu positioning, lighting, animations (intro, idle, and outro), gameplay state change, menu design, engineering restrictions, and performance.

![Rise of the Tomb Raider menu](/privatebebo/img/TombRaider_menu.jpg)  
_This screenshot from Rise of the Tomb Raider shows how menus can be integrated within gameplay._

![Rise of the Tomb Raider submenu](/privatebebo/img/TombRaider_submenu.jpg)  
_Rise of the Tomb Raider: Another example of how in-game scenes and assets can be integrated to support UI menus._

![Halo 5 menu](/privatebebo/img/Halo5_menu.jpg)  
_Halo 5: Layout of 3D assets can help immerse the player at the level of main menu._

<br>
