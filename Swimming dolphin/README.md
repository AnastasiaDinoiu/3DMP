# Swimming dolphin mechanism

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

## Software
The software I used for the 3D modeling and the rendering is Autodesk Fusion 360.

## Mechanism's creator
* https://www.myminifactory.com/object/3d-print-99277
* https://www.youtube.com/watch?v=Ot3GTSwU0ZI
<img src="https://user-images.githubusercontent.com/75319867/117357254-60bd4200-aebd-11eb-9415-53cc21307200.jpg" alt="drawing" width="400" style="width:200px;"/>

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

## Checkpoints
* Checkpoint 1
  * Choose project
  * Divide your project into components
* Checkpoint 2
  * Finish the mechanism
* Checkpoint 3
  * Add joints, motion links and create motion study