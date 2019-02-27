---
layout: default
title: Projects
description: Welcome to my Project Library!
---

## Hardware
* * *

### DAW Macro Footswitch Pedal 
I commenced this project to enhance my music composition workflow. As an avid pianist, I love to compose music just as much as I love to perform it. A few years back, I realized that I had difficulty with recording multiple takes in a single recording session. Frustrated by the inefficiencies of the computer keyboard 'shortcuts,' I decided to come up with my own solution to avoid pressing 'spacebar, delete, enter, and R' every time I wanted to re-record a take while composing a song.

To start, I drafted many iterations of the design. I eventually landed on a configuration that utilized the most-used keys when recording a take: spacebar (to stop the current recording), enter (to move the play head back to the start), 'ctrl' and 'z' to be pressed at the same time to undo the recording, and 'r' to record again. I optimized this process with 5 arcade-style buttons and 2 smaller buttons that would be easily pressed in various combinations with a foot. A schematic will be added shortly showing the commands for each key.

In terms of hardware, the main structure is a wedge comprised of 2 pieces of plywood. The angled design enables for a comfortable foot rest while recording. The wiring was done in accordance to the pin-outs of each keyboard controller. Prior to project commencement, a spreadsheet was used to record each corresponding key-out for each pair of pins on each controller. Two controllers were used to accomodate for a faulty controller. USB power was used to power LEDs in the 2 smaller switches, as well as 3 LEDs on the underside of the plywood.

Front                                                              |  Bottom
:-----------------------------------------------------------------:|:-------------------------------------------------:
![DAW_Footswitch 1](/assets/Project_Pictures/DAW_Footswitch1.jpg)  |  ![DAW_Footswitch2](/assets/Project_Pictures/DAW_Footswitch2.jpg)

### MIDI Keytar
This was a fun project to explore music and technology, which was inspired by Herbie Hancock, a famous jazz musician who started out in electrical engineering! Using an M-Audio Keystation 49 MIDI keyboard, I ran bolts through each side of the keyboard chassis to create mount points for straps. I then added a Samson Graphite MF8 mounted with a wireframe mesh to add additional MIDI transport controls. This keytar performs nearly identically to modern day equivalents priced at over $1000!

![Keytar](/assets/Project_Pictures/Keytar.jpg)

### Bluetooth Audio Receiver
Using an old BlueAnt Bluetooth Speakerphone (back when these were a thing), I soldered a ¼ inch female audio jack to the amplification circuit, allowing for bluetooth music streaming from a phone to an external stereo system.

![Blueant](/assets/Project_Pictures/Blueant.jpg)

### Robotic Hand
This project was made for a Biology project on Biomechanical Engineering in Grade 12. After watching various YouTube tutorials, I decided to construct a robotic hand that mimics real-time movement of a glove worn by the human hand. The project allowed me to explore the uses of linear resistive control with an Arduino microcontroller and 5 hobby servos. Since flex sensors were not readily available to me, I constructed them using pairs of aluminum foil tape, cardboard, and electrical tape. After multiple calibrations, each sensor was ready for use the glove. In the end, I had a working model of a myoelectric limb, a type of prosthetic used for amputees or those with congenital limb loss.

![Robotic_Hand](/assets/Project_Pictures/Robotic_Hand.jpg)

### Server/Network Configuration
I have configured and built many servers over the span of my teenage years. Being into video games such as Minecraft when I was younger, I have always been interested in server configuration - static and dynamic IP addresses, port forwarding and router security. I have revamped Dell PowerEdge T100 and 2950 servers, changing RAM and installing hard drives and SSDs. Using old Lenovo office computers, I have created a personal file storage cloud. Using FreeNAS and multimedia plugins such as Plex Media Server, I've set up movie and music streaming services that may be accessed worldwide through portforwarding and SSH utilities. In addition, I have experimented with Windows Server R2012 and Apple OS X Server (through VMWare's ESXi) for file backup. I am constantly trying to improve my networking knowledge, for example, I used an old Cisco E2500 to test-install DD-WRT software and convert it to a repeater for my home network.

### Desktop/Laptop Configuration
Outside of servers, I enjoy building computers. I have built an AMD Threadripper system for a friend (installing watercooling for a Ryzen 2700X), as well as my own dual-boot Windows/Mac OS system on Haswell Architecture. In the meantime, I enjoy revamping various Apple notebooks, upgrading RAM and SSDs in pre-2010 MacBook and MacBook Pro models. 

### Computer Server Cabinet
This was built to complement that home media servers that I have configured. The cabinet was first drafted by hand and the area of wood required was calculated. Built from  5/8" plywood, this cabinet houses 5 servers, as well as a monitor on a swing arm. The unit also functions as a standing desk for enhanced ergonomics while working.

Front-Down                                                        |  Front
:----------------------------------------------------------------:|:-------------------------------------------------:
![Server_Cabinet1](/assets/Project_Pictures/Server_Cabinet1.jpg)  |  ![Server_Cabinet2](/assets/Project_Pictures/Server_Cabinet2.jpg)

## Software
* * *

### Java | 2D Wave Game
This project was created for a highschool computer science course. I led a team to develop a 2D platformer game using object-oriented programming, delegating tasks to individuals and documenting the project in weekly summation journals. To improve project organization, I used IPO charts, pseudocode, and software development lifecycles. Most of what I learned for this project came from YouTube tutorials - the channel 'RealTutsGML' was used as a primary resource. The following picutres show some gameplay.

![WaveGame_1](/assets/Project_Pictures/WaveGame_1.png)

![WaveGame_Boss](/assets/Project_Pictures/WaveGame_Boss.png)

![WaveGame_Lose](/assets/Project_Pictures/WaveGame_Lose.png)

### Java | Inventory Management Software
I developed this application in highschool as well - it takes inputs for item information, and returns stock information in a GUI. 

![InventoryTracker_AddItem](/assets/Project_Pictures/InventoryTracker_AddItem.jpg) ![InventoryTracker_DiscontinueItem](/assets/Project_Pictures/InventoryTracker_DeleteItem.jpg)

### MATLAB | Robot Position Curve Fitting
I have significant experience programming in MATLAB, using scripts for techniques such as vector and matrix operations, numeric and symbolic computation, 2D and 3D graphing, polynomial curve fitting, derivatives, linear systems, and parameterization. Using MATLAB, I imported robot position data and used polynomial curve-fitting techniques to find optimal models for position, velocity and acceleration. Below are some graphs from the final project document.

![MATLAB_RobotGraph_1](/assets/Project_Pictures/MATLAB_RobotGraph_1.png) ![MATLAB_RobotGraph_2](/assets/Project_Pictures/MATLAB_RobotGraph_2.png)

### C | Chord App
An idea in the making. Essentially, the application accepts user input for a type of chord, and then the software will present a staff and the notes to play the chord on a piano. It may also list scale degrees.


[<Back to Home](./)
