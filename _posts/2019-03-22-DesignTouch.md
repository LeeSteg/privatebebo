---
layout: post
title: Design for the Senses
subtitle: Touch  Sound  Sight
tags: [Getting Started, Design]
---

The best games are most immersive because they make use of the most senses.  
The more senses you want to design for, and the more immersive experience you want to create, the more planning you have to do. Because using the senses of taste and smell in games is not mainstream yet, we’ll focus on the other three senses: touch, sound, and sight.

![Touch](/img/Design_Common_Senses_long.png)

## Touch
Most console games use a controller that has a set number of buttons and analog joysticks. Because interaction through these elements isn’t as fast or precise as through a mouse or direct touch, you should understand the limitations of your controller device.

The controller’s layout can make or break the players’ experiences with a game. Design your controls to feel as natural as possible. One of the first things to consider is how each button will be used in the gameplay.

| Input Device | Avg Screen Size | Distance/Screen Size | Size/Distance % | Method of Interaction |
| :------ |:--- | :--- | :--- | :--- |
| Touch | Small 3.5" | 1' / 12" | 29 | Tap, pinch, swipe |
| Mouse & Keyboard | Medium 20" | 3' / 36" | 56 | Mouse & Keyboard, many inputs. Pinpoint accuracy |
| Controller | Large 40" | 10' / 120" | 33 | Grid, button navigation. Limited button input. |

<br>

Console games have been around for decades, so a number of interactions have become standard and are even expected by players today.

### Microsoft's Xbox One
![Xbox One controller](/img/Xbox_Controller.jpg)

Menu navigation controls of the Xbox One controller
- **A**: enter, select, confirm
- **B**: back, cancel
- **X**: details
- **Y**: details
- **Menu**: menu toggle
- **View**: map or chat
- **D-Pad**: navigation
- **Left Stick**: navigation
- **Right Stick**: text or list scroll
- **Left Bumper**: sub-menu, left navigation
- **Right Bumper**: sub-menu, right navigation
- **Left Trigger**: page-up navigation
- **Right Trigger**: page-down navigation
- **Nexus**: Xbox Home

<br>
 
### Sony's Playstation Controller

![PS4 controller](/img/PS4_Controller.jpg)

The layouts of the PlayStation and Xbox controllers are very similar. One major exception is the touchpad, which was introduced in PlayStation 4 and offers additional opportunities for input.  
Menu navigation controls of the PS4 controller
- **CROSS**: enter, select, confirm
- **CIRCLE**: back, cancel
- **SQUARE**: details
- **TRIANGLE**: details
- **Options**: pause menu, map
- **Share**: share
- **D-Pad**: navigation
- **Left Analog**: navigation
- **Right Analog**: text or list scroll
- **L1 Bumper**: sub-menu, left navigation
- **R1 Bumper**: sub-menu, right navigation
- **L2 Trigger**: page-up navigation
- **R2 Trigger**: page-down navigation
- **PS Home**: PS Home
- **Touch Pad**: chat keyboard, directional cursor, map

<br>

### Nintendo's Switch Controller

![Switch controller](/img/Switch_Controller.jpg)

The Switch controller is similar to the Xbox and PlayStation controllers but can also be split into two controllers that have similar but limited layouts.  
Menu navigation controls of the Switch controller
- **B**: enter, select, confirm
- **A**: back, cancel
- **X**: details
- **Y**: details
- **- Button**: text/list scroll
- **+ Button**: navigation
- **Directional Buttons**: navigation
- **Left Stick**: navigation
- **Right Stick**: text or list scroll
- **L Button**: sub-menu, left navigation
- **R Button**: sub-menu, right navigation
- **ZL Trigger**: page-up navigation
- **ZR Trigger**: page-down navigation
- **Home**: Nintendo Home
- **Capture Button**: map/chat

<br>

### Microsoft's Xbox Adaptive Controller

![Xbox Adaptive controller](/img/Xbox_Adaptive_Controller.jpg)

Designed primarily to meet the needs of gamers with limited mobility, the Xbox Adaptive Controller is a unified hub for devices and is designed to make gaming more accessible. It works with a range of external devices (such as switches, buttons, mounts, and joysticks) to create a customizable controller experience unique to a player.

<br>

### Layouts of controllers
Different layouts of controllers have been designed to suit different genres of games, and in some genres, several layouts of controllers are used. Use the following common, genre-specific layouts as a guide in your game design: 


| Xbox | PS4 | Switch | Driving & Flying | Action & Shooter | RTS & Simulation | Puzzle & Platform | Fighting | Sports |
| :--- |:--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **A** | **Cross** | **B** | Speed Shoot | Jump /Interact | Select | Jump | | Shoot |
| **B** | **Circle** | **A** | | Crouch | | Duck | | Pass |
| **X** | **Square** | **Y** | Hand Brake | Interact Reload | | | | Hit |
| **Y** | **Triangle** | **X** | | Switch Weapon | | | | Change Player|
| **D-Pad** | **D-Pad** | **Directional Buttons** | | Items /Weapons Shortcuts | Items /Weapon Shortcuts | Navigation | | Camera Zoom |
| **Left Stick** | **Left Analog** | **Left Stick** | Move | Move | Move | Move | Move | Move |
| **Right Stick** | **Right Analog** | **Right Stick** | Camera | Camera | Reticle | Camera | Camera | Camera |
| **Left Bumper** | **L1 Bumper** | **L Button** | | /Projectile | | | | Line Shift |
| **Right Bumper** | **R1 Bumper** | **R Button** | | /Use Item & Melee | | | | Call Play |
| **Left Trigger** | **L2 Trigger** | **ZL Trigger** | Acelerate | Aim & Zoom | | | | Key Player |
| **Right Trigger** | **R2 Trigger** | **ZR Trigger** | Brake | Shoot & Attack | | | | Show Play |
| **Menu** | **Options** | **Home** | Pause Menu | Pause Menu | Pause Menu | Pause Menu | Pause Menu  | Pause Menu |
| **View** | **Share** | **Capture** | Map Menu | Map Menu /Share | Map Menu | Map Menu | Map Menu | Map menu |
| **Nexus** | **PS Button** | | Home | Home | Home | Home | Home | Home |
| | **PS Touchpad** | | | Menu Inventory | Map | | | |
| | | **- Button** | | | | | | |
| | | **+ Button** | | | | | | |

<br>

### Mouse and keyboard
Interaction through the mouse is similar to interaction through touch, in that the user can perform any action with pinpoint accuracy, on any part of the screen. The keyboard is a powerful tool in its own way, because it offers a wide variety of button and key inputs—and an even greater variety of combinations—for communication and navigation.

![Mouse & Keyboard](/img/Mouse_Keyboard.jpg)

<br> 

### Converting the Mouse & Keyboard to the Controller
Many games are first developed for a mouse and keyboard, which offer many buttons and are relatively easy to implement. The mouse also makes it easy to master the skill of moving and aiming the camera with pinpoint accuracy. 
In combination, the mouse and keyboard allow for a great development platform on which new features of a game can be tested out. However, converting the complex interactions possible with a mouse and keyboard to interactions through a console can be difficult, because the latter has a fixed number of button inputs. In addition, an analog joystick is not as fast or accurate as the mouse.
The following are some of the common mouse and keyboard input designs adapted for a controller:

| Mouse & Keyboard | _Action_ | Controller |
| :--- | :--- | :--- |
| Left Mouse Click | _Jump, Shoot and Select_ | A |
| | _Duck, Pass_ | B |
| | _Interact, Reload, Hand Brake_ | X |
| | _Switch Weapon_ | Y |
| | _Map Menu_ | View |
| Esc | _Pause/Menu_ | Menu |
| 1 thru 0 | _Weapon/Item shortcuts_ | D-Pad |
| W | _Player Up/Forward_ | Left Stick, Up |
| S | _Player Down/Backwards_ | Left Stick, Down |
| D | _Player Right_ | Left Stick, Right |
| A | _Player Left_ | Left Stick, Left |
| Mouse | _Camera/Weapon Aim_ | Right Stick |
| | | Left Bumper |
| | | Right Bumper |
| | _Aim, Accelerate_ | Left Trigger |
| | _Shoot, Brake_ | Right Trigger |

<br>

{: .box-warning}
**Tip:** Use the face buttons to test your core gameplay action. Use the shoulder and trigger buttons to modify actions. Use the D-Pad to select modes and abilities. 

