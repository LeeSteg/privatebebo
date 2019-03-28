---
layout: post
title: Design Vocabulary
subtitle: Terms and topics to know
tags: [Terminology]
---


### HUD
The heads-up display, or HUD, is an in-game UI used extensively in core gameplay. The information communicated through the HUD varies according to the genre and game. Although certain HUD components are expected in some game genres, a game designer might decide to replace them with in-game solutions.

The following are some of the popular HUD components used in console games: 
- Health/Energy bar
- Reticle
- Compass/Minimap
- XP/Score
- Timer/Speed
- Item/Ammo Count
- Quests/Objectives
- Achievements
- Contextual gameplay prompts
- Pop-up windows

<br>

### Frontend (FE) menus
FE menus are ubiquitous and provide players with a vast array of customization settings:
- Guiding the player into a game
- Reviewing statistical information
- Customizing gameplay
- Customizing characters
- Modifying the game settings
- Saving the progression
- Upgrading and making in-game purchases
- Inviting friends to play
- Broadcasting a game

{: .box-warning}
**TIP:** Before designing any menus, first design the FE menu flow. At a high level, the FE menu shows the screens and components necessary to build out the menus for the game. Working out all the scenarios first and getting team consensus will give the engineering game design, UX design, and sound departments a better understanding of how to budget resources and time against the deliverables.

<br>

### WCG: Wide Color Gamut
WCG is the range of colors that can be rendered on HDR (High Dynamic Range) television screens, monitors, and phones. A typical SDR (Standard Dynamic Range) television or monitor has a color depth of 8 bits and 16.7 million (256 x 256 x 256) colors available. On the other hand, a typical WCG device has a color depth of 10 bits and 1.07 billion (1024 x 1024 x 1024) colors available. Thus, WCG produces a far richer, smoother quality of color, and this enhances the realism and accuracy.

![SDR HDR comparison](/privatebebomalaka/img/SDR_HDR_comparison.png)

{: .box-warning}
**TIP:** Certain color gradients cause banding. You can reduce the banding artifact by adding other graphical elements or by adding a subtle noise filter.

<br>

### HDR: High Dynamic Range
HDR is the range of luminance (measured in nits) that a television, monitor, or phone can display. HDR is also used to describe WCG, because the color and luminance are combined in HDR displays.

Increasing luminance improves the image quality enough to render subtleties of shadows, dark areas, true glow, and bursts of light.

In the past, UI designers had to be concerned only with RGB colors. With HDR, there is also luminance to consider. 

The standard spec for sRGB is 80 nits, but modern SDR TVs and monitors can render up to 120–300 nits. Smart phones can render up to 550 nits, to ensure they are readable in sunlight. HDR TVs can render up to 1000 nits, with even higher numbers coming in the near future.

![NIT output](/privatebebomalaka/img/HDR_Devices.jpg)

{: .box-warning}
**TIP:** Using too many bright objects in HDR might fatigue players’ vision and cause them to stop playing. To make the most of HDR, use it sparingly in areas such as focus states, damage indicators, location beacons, attention focus effects, notifications, and moment of celebration.

<br>

**NOTE:** The images below have been modified for viewing on an SDR monitor, to showcase the difference between SDR and HDR. 

![HDR Forza screenshot](/privatebebomalaka/img/Forza7_SDR.png)
_Forza 7 SDR screenshot:_ Bright and dark areas lack detail in SDR mode.

<br>

![SDR Forza screenshot](/privatebebomalaka/img/Forza7_HDR.jpg)
_Forza 7 HDR screenshot:_ Notice the detail in the sunset, the clouds, and the shadow under the car’s grill. The subtle details make the image more visually dynamic and add to the artfulness of the scene.
