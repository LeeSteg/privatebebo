---
layout: post
title: Popup Menus
subtitle: Overview of popup menus
tags: [Menus]
categories: [Menus]
---

Use pop-up screens to immediately call the player’s attention to game-changing and game-blocking events. Pop-up text must be concise, direct, and very easy to comprehend. In a message that requires a Yes/No answer, make the question as clear as possible. Avoid double negatives and ask a direct question that can be answered only with “Yes” or “No”.

Include a Confirm button (A) and Cancel button (B). In some cases, provide a list of choices.  
**Examples:**
- **Good:** Would you like to quit the game? Yes/No
- **Bad:** Do you want to continue or quit the game? Yes/No

To enhance the immersive experience, many games apply a semi-transparent overlay to darken the screen at certain times. This technique might not work well if the screen being obscured contains distracting visuals. Here’s how you can remedy this issue:

- Make the color of the pop-up’s background solid, to completely cover any distracting information.
- Before displaying the pop-up screen, use a shader effect to blur out the distracting information.

This technique offers the best results, especially in games developed for HDR and WCG.

![Popup Menu Blur](/img/Examples_PopupMenuBlur.jpg)  
_Forza Horizon 3: the pop-up uses a blur shader to obscure all menus and HUD components. This helps the player focus on the information in the pop-up._

![Popup Menu Overlay](/img/Examples_PopupMenuOverlay.jpg)  
_Jurassic World Evolution: the pop-up obscures the HUD components either completely or partially, through a subtle transparency effect._

<br>
