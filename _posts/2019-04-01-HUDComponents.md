---
layout: post
title: HUD Components
subtitle: Overview of common HUD components
tags: [HUD, Design]
categories: [HUD]
---

In the HUD, Information graphics are often layered on top of the gameplay. This helps players keep track of the core gameplay information, such as the score, health, time, item totals, location, and direction.

### Health

The health of a character or vehicle can be displayed as a number, percentage, graphic icon, or health bar. The most important thing to communicate is the range of health, from full to empty:
- Most health bars show full health on the left and low health, or death, on the right.
- Some health bars also use different graphics and colors to show the state of bonus health.

{: style="text-align:center"}
![Common Healthbars](/privatebebomalaka/img/HUD_Healthbars.png)

A good practice is to notify the player when a character loses or gains health. Many games show the percentage or amount of health being lost or gained. In some instances, the health bar or number will flash when the character’s health gets too low.

{: style="text-align:center"}
![Healthbar States](/privatebebomalaka/img/HUD_Health_Loss.gif)
{: style="text-align:center"}
![Healthbar States](/privatebebomalaka/img/HUD_Health_Gain.gif)
{: style="text-align:center"}
![Healthbar States](/privatebebomalaka/img/HUD_Low_Health.gif)

Place the health widget close to the core action, such as in the upper-left or upper-right corner, or in the bottom center. Placing the health bar close to the border of the screen will ensure it doesn’t cover the gameplay and lets the player assess the health state at a glance.

<br>

The following examples illustrate how the Health component can be used in various types of games:

![HUD Health genre placement](/privatebebomalaka/img/HUD_Health_genres.gif)

<br>

### Score

The score component of the HUD provides a multitude of stats:

- Game score
- Total points by team
- Currency remaining for consumables and upgrades
- Player’s progression through the game
- High score
- Comparison of the current score with a high score

When the player’s score increases, the score should provide feedback by

- Increasing the total
- Adding a flashing graphic on the score widget
- Displaying a cut scene for an important score milestone

Display the score in the top left, top middle, or top right, opposite of the health stats. In sporting games, display the score at the bottom center, to mimic television broadcasts. Camera focus and gameplay will also dictate the placement of these HUD components.

The following examples illustrate how the Score component can be used in various types of games:

![HUD Score genre placement](/privatebebomalaka/img/HUD_Score_genres.gif)

<br>

### Timers

A timer is usually integrated with the Score component and displayed in the top center or bottom center of the screen. During the final countdown, the timer can alert the player by flashing or by changing color, with sound effects added in the final 5–10 seconds.

The following examples illustrate how the Timer component can be used in various types of games:

![HUD Timers genre placement](/privatebebomalaka/img/HUD_Timers_genres.gif)

<br>

### Ammo Count

You have many techniques at your disposal:

- Display the weapons and ammo counts close together
- Indicate when the weapon runs out of ammo
- Change the count’s color
- Show an empty ammo clip graphic
- Use a sound effect if the player tries to make a shot with an empty gun clip

![Common Ammo Count](/privatebebomalaka/img/HUD_Ammocount.png)

Shooter games commonly use first-person and third-person POVs. With the third-person POV, the character is usually in the bottom-center of the screen. To avoid obscuring the character, display the ammo count in the upper-right or upper-left corner of the screen. With the first-person POV, the focus is in the center of the screen, so the ammo count is best placed in the mid-bottom part of the screen. 

Newer HUD designs integrate the ammo count with the weapon itself, so the traditional ammo count component may get eliminated.

The following examples illustrate how the Ammo Count component can be used in various types of games:

![HUD Ammo genre placement](/privatebebomalaka/img/HUD_Ammo_genres.gif)

<br>

### Reticle

For targeting-related effects, implement a reticle (or a cursor) to indicate an interaction or the direction of a projectile. Pick a color that will make the reticle stand out in the game world, and give the reticle a tinted outline.

To indicate a direct hit or a positive interaction area, show a state change. To indicate the interaction target, animate the reticle or change its shape or color. 

![Common Reticle States](/privatebebomalaka/img/HUD_Reticle_States.png)

Let the player customize the reticle for different weapon types, items in the inventory, and interactions.

In games that use first-person and third-person POVs, the keep the reticle in the center of the screen and implement the Right Stick to control the camera. In Real-Time Strategy (RTS) and top-down gameplay, implement the Right Stick to move the reticle and to pan the screen by moving the cursor to the edges.

The following examples illustrate how the reticle can be used in various types of games:

![HUD Reticle genre placement](/privatebebomalaka/img/HUD_Reticle_genres.gif)

<br>

### Compass

The Compass component shows the direction in which a player, teammates, or objective moves within the game world.

Because the compass is often used in the first-person and third-person POVs in an Open World scenario, place this component in the top center of the screen.

The following examples illustrate how the compass can be used in various types of games

![HUD Compass genre placement](/privatebebomalaka/img/HUD_Compass_genres.gif)

<br>

### Minimap

Implement a small top-down map in games where the player must know the location of teammates, enemies, and various other elements. The mini-map may also include a compass, off-screen indicators, and objective markers.

The mini map should occupy no more than 1/8th of the screen, so avoid displaying too many details on it. Because the mini map provides information that is secondary to the gameplay, place it in the bottom corners of the screen, opposite of where most gameplay takes place.

![HUD Minimap genre placement](/privatebebomalaka/img/HUD_Minimap_genres.gif)

<br>
