# Swimming dolphin mechanism
<img src="https://user-images.githubusercontent.com/75319867/119235779-d0c5fc00-bb3c-11eb-9359-19a855b7e867.png" alt="drawing" width="950" style="width:200px;"/>

## Short description
The swimming dolphin mechanism is based on the rotation of the main crank, which makes the pistons slide up and down alternatively. This way, the mechanism simulate a swimming dolphin.
I chose this mechanism for my final project of the 3D Modeling and Printing course because i find it very beautiful and also exciting.

## How it works
___Main components___
* Case
* Crank
* Crank holder
* A small and a big gear + a holder for the second one
* Waves
* Pistons
* Dolphin pieces

<img src="https://user-images.githubusercontent.com/75319867/119235997-c5270500-bb3d-11eb-885e-8f8d48aa019a.gif" width="470"> 

The handle, which is connected to the big gear, needs to be powered by a rotation movement. In its rotation, the big gear powers the small gear, giving to the second one also a rotation movement, but in the opposite direction. This way, the main crank, which is directly connected to the small gear, starts to rotate with it and the pistons, which are positioned on the disks, moves up and down. Because the dolphin pieces are connected to the pistons, the mechanism manage to simulate the swimming dolphin effect.

To make the mechanism work in Fusion 360, I used the following ___joints___:
* __rigid group__ for: 
  * crank + its holder + small gear
  * big gear + its holder
  * pistons + its dolphin pieces
  * case + waves
* __revolute joint__ for:
  * crank
  * big gear
* __slider joint__ for:
  * pistons + its disks
I also used motion link for the small an big gear and a motion study for the whole mechanism

## How to power the mechanism
The main joint which needs to be powered to make the mechanism work is the revolute one, connected to the big gear. Also, in order to see the mechanism work in the easiest way, I made a motion study in which I selected all the joints.

<img src="https://user-images.githubusercontent.com/75319867/119236014-d1ab5d80-bb3d-11eb-90da-a08c2cac77cd.gif" width="465"> <img src="https://user-images.githubusercontent.com/75319867/119236025-d96b0200-bb3d-11eb-9d6f-a383eb662583.gif" width="465">

## Software
The software I used for the 3D modeling and the rendering is Autodesk Fusion 360.

## Files
This repository contains .f3d files with the whole project, from every checkpoint. It also contains images, renderings (.gif, .png) and .stl files with every component.

## Mechanism's creator
* https://www.myminifactory.com/object/3d-print-99277
* https://www.youtube.com/watch?v=Ot3GTSwU0ZI

This is how Jwoong's final project looks like:

<img src="https://user-images.githubusercontent.com/75319867/119272761-464ecc80-bc10-11eb-849f-43ec7d612364.jpg" alt="drawing" width="405" style="width:200px;"/> <img src="https://user-images.githubusercontent.com/75319867/119272673-ca548480-bc0f-11eb-9fc6-b0bd93506ff6.gif" alt="drawing" width="400" style="width:200px;"/>

## Requirements
* Start the design from canvases or sketches.
* Respect FUSION RULE NUMBER ONE. 
* Save multiple versions and suggestively name them.
* Properly use and name bodies, components, joints, construction planes, etc. 
* Render the object applying appearance and scene (color scene or environment). 
* Save the renderings as photos and as a VIDEO / GIF Render. Upload them to GitHub as well.
* Add joints, motion links and joint limits. 
* Create motion studies.
* The mechanism needs to work properly! 