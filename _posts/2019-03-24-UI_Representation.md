---
layout: post
title: Representation of UI
subtitle: Different types of HUD Design 
tags: [Knowledge, UI]
categories: [Knowledge]
---

The four types of HUD UI are Non-Diegetic, Diegetic, Spatial, and Meta. Each UI has its pros and cons, as well as distinct budgeting requirements for art direction, pre-production, implementation, and design.

![4 Types of HUD](/privatebebomalaka/img/HUD_4types.png)

<br>

## Non-Diegetic UI
Non-Diegetic UI is detached from the gameplay. The characters do not interact with the UI elements, and the UI is the final layer of graphics rendered on top of the gameplay. Most games are built with Non-Diegetic UI.

Art direction can be influenced heavily by the in-game environment, and it can be based on the elements of the story or focus on making information easy to read. A well-designed UI might influence art direction, so work closely with the Art Director to create a style guide that will complement both the game and UI.

Start pre-production of a Non-Diegetic UI with a list of the core elements of gameplay. Next, block out each UI component on top of the screenshots of the game. Work with the game designers to figure out where to place the gameplay camera and the core information to be communicated to the player. 

Prototyping the functionality, size, and placement of the UI elements will help drive the overall design of the UI. In some cases, you might find alternative ways to display information in the game without using the Non-Diegetic technique.

Implementation of a Non-Diegetic UI usually involves a UI artist or designer, who will create assets that will be implemented in the UI’s middleware or hardcoded into the game engine. Once these assets are built, the UI designer can start adjusting the motion, timing, opacity, color, and placement of each UI element.

![Non Diegetic UI](/privatebebomalaka/img/UI_NonDiegetic.jpg)
_Screenshot from Battlefront_

When designing a Non-Diegetic UI, focus on legibility, timing, and positioning of each element in the gameplay.

The **pros** of using a Non-Diegetic UI:
- It is easy to design and implement.
- Core development of the UI is not dependent on other areas of the game.
- Because the UI is the final layer to be rendered, its legibility is not affected by the gameplay.
- Performance of the UI is measurable early in development.

The **cons** of using a Non-Diegetic UI:
- It might become cluttered and cause information overload.
- It might obstruct gameplay.
- It might break the illusion of a completely immersive experience.
- It’s limited to a 2D design with fewer effects and less lighting.

<br>

## Diegetic UI
Diegetic UI is integrated with games like The Division and Dead Space. Both players and characters are interacting with the UI at the same time, and this results in a much more immersive experience.

The art direction of a Diegetic UI tends to follow a hi-tech look commonly seen in sci-fi movies and television. Part of the reason for using this visual direction is to present legible information and avoid complicated textures and ornate visual elements that obscure the information conveyed through the UI .

As with Non-Diegetic UI, pre-production of Diegetic UI begins with a list of the gameplay’s core elements that will be communicating information to the player. Few games rely on Diegetic UI completely: because the UI is rendered in the game, there will be a performance hit, as well as the dependence on many production resources. Choose the core UI elements that keep the player immersed in the game and create prototypes very early in pre-production. Because the Diegetic UI involves in-world objects, characters, camera setup, and custom animation, ensure that you have full support of the team and that the budget for team resources is approved.

One example of Diegetic UI is the design of the main character in Dead Space, where the developer wanted to display the health indicator on the character’s space suit. This involved getting concept artists, character modelers, tech artists, and engineers to work together to design a health meter in the very early stages of pre-production, and to prototype and test whether this Diegetic UI design would actually work in the game.

When designing a Diegetic UI, focus on legibility of each element. In addition, work with the game designers to ensure that the UI components do not interfere with the core gameplay and that the player’s progression is not obstructed.

![Diegetic UI](/privatebebomalaka/img/UI_Diegetic.jpg)
_Screenshot from The Division_

The **pros** of using a Diegetic UI:
- The UI is integrated with the gameplay, so the experience is more immersive.
- Less UI on the screen means more screen space available for the game.
- The design is reduced to the core UI elements, and this makes information easier to comprehend.
- Because Diegetic UI is used by few publishers, applying it in your design could help your game stand out from the competition.

The **cons** of using a Diegetic UI:
- Core development of the UI is dependent on other areas of the game.
- Implementing the UI requires many production resources.
- More areas in the UI require bug fixes and polishing.
- Performance of the overall rendering of the game might take a hit.

<br>

## Spatial UI
Spatial UI comprises effects, trails, and character outlines and is commonly used in combination with Diegetic or Non-Diegetic UIs. Games like Last of Us, Uncharted 4, and Assassin’s Creed use Spatial UI to draw lines around enemy characters and to help identify them on the screen.

Spatial UI requires less art direction, because it consists primarily of in-game effects applied for the purpose of game design. 

Begin by creating a list of the core elements that will be communicating information to the player. Once the core elements are identified, involve technical artists and engineers to implement shaders and logic for the UI. Early stage prototyping in pre-production is encouraged and should identify any potential performance and rendering issues. However, UI elements might also be added during production and tested for their effectiveness in the game.

The design of the Spatial UI is based on the shaders written by technical artists and engineers. The choice of colors and the timing of the UI is usually determined by game and UX designers.

![Spatial UI](/privatebebomalaka/img/UI_Spatial.jpg)
_Screenshot from Assassin's Creed: Syndicate_

The **pros** of using a Spatial UI:
- UI is integrated with gameplay; the experience is more immersive.
- UI provides a clear and distinct way to identify characters and objects in the game.
- Generally, there is less of a performance hit than with the Diegetic UI, and implementation is easier.

The **cons** of using a Spatial UI:
- Implementation requires additional production resources.
- Greater performance hit is sustained than with a traditional, Non-Diegetic UI.
- The game is visually limited to the art direction of the UI.

<br>

## Meta UI
Meta UI is not used to present anything but only to create visual effects by desaturating the UI or gameplay or by adding an in-game element such as blood, mud, or water splatter. It is common to use Meta UI to convey weather conditions and environmental effects.

Meta UI tends to be more of an Art Director’s call than that of a UI artist or designer. It adds ambiance to the game and is a subtle element used to communicate the UI information.

Because most Meta UIs are created using textures and shaders written for the game, you will have to identify the areas where full-screen effects will be used. These areas do not need to be created in pre-production, because they are typically used as secondary elements that address changes in health or in environment state.

To implement the Meta UI, a tech artist or an engineer will write a shader and the engineer and UI artist will implement the state conditions.

Aside from being used to change the ambiance and weather states, Meta UI can be used to show the health states (Low Health, Death, and Power) by: 
- Rendering a shader to reduce the screen saturation
- Changing the overall color palette to night vision, heat vision, surveillance mode, and so on

Meta UI is typically used in conjunction with other UI techniques.  
![Meta UI](/privatebebomalaka/img/UI_Meta.jpg)
_Screenshot from Forza Horizon 3_

The **pros** of using a Meta UI:
- UI is usually a full-screen effect that involves the entire game.
- UI clearly and distinctly identifies a state change in the game.
- UI works well as a treatment that supplements the traditional Non-Diegetic UI.

The **cons** of using a Meta UI:
- Implementation requires additional production resources.
- UI is limited to screen effects and, therefore, offers less fidelity in communicating detailed information.

<br>
