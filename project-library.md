---
layout: default
title: Projects
description: Welcome to my Project Library!
---

## Hardware
* * *

### MLH - To the Moon and Hack 2020 - MuscleMath
[GitHub Project](https://github.com/eyfb/MuscleMath)  
[Devpost Submission](https://devpost.com/software/muscle-math)  

This was a fantastic hackathon to attend during the pandemic in the summer of 2020. In this project, I was able to apply what I had learned from working over the summer as a Software Engineering Intern. With knowledge of Node.js, HTML and CSS, I learned to use chart.js to graph data fetched asynchronously from a csv, and I used csv-writer to append data to a csv. I also learned to use Express.js for routing pages. Coming out of this hackathon, I gained a newfound appreciation for web development, and I am continuing to learn more about web technologies on UofT's newly founded Cloud Club software team.

### Split Mechanical Keyboard
Built over the summer of 2020 as a fun side project, this keyboard is split for better ergonomics, and features wrist rests for reduced strain on wrists. This project was built using the following [thingiverse project](https://www.thingiverse.com/thing:2879329). Cherry MX Red mechanical switches were soldered with a wire and diode matrix. The firmware was generated from this [tool](https://kbfirmware.com/) and flashed to an Arduino Pro Micro. One addition I made to this project was a reset push-button to enable firmware flashing with updated keyboard layers/macros. The case was 3D printed using an Ender 3 Pro with tranparent and white PLA.
  
![split_mech](/assets/Project_Pictures/split_mech.jpg)

### MLH - MakeUofT 2020 - StayEnlightened
[GitHub Project](https://github.com/joonhosung/StayEnlightened)  
[Devpost Submission](https://devpost.com/software/stayenlightened)  

This project was created to solve a problem in study spaces with motion-activated lighting: when students are studying (i.e. not moving), lighting will turn off automatically, creating a distraction and making it hard to maintain focus. Our team remedied the problem by using a webcam with OpenCV, Python, Arduino, and the Qualcomm Dragonboard 410C to detect not only motion, but human presence, ensuring the lights are kept on until no humans are present. In this project, I learned how to use OpenCV and Python to grab individual frames from a Logitech webcam. I also integrated the Grove Base Shield on the Qualcomm DragonBoard 410C and implemented a PIR sensor to detect motion using Arduino. Finally, I wrote code to transmit and receive serial data between the Arduino and Python OpenCV camera code.

### Chord Machine - FPGA Audio Synthesizer
This was a project for a Digital Systems course in second year ECE at the Unversity of Toronto. Using the DE1-SoC FPGA and Quartus Prime 18.1, I programmed the audio chipset on the DE1-SoC board to create square, triangle and saw waveforms (Verilog). The board can interface with a PS/2 keyboard to allow the user to play along with a built-in 4/4 looper. More details can be read about [here.](https://github.com/iWebster28/Music/blob/master/ChordMachine/ChordMachineFinal/ECE241%20Final%20Project%20Report%20-%20Ian%20Webster%20-%20Github.pdf) You can also watch a YouTube video of it [here.](https://youtu.be/eF6zlbV_rJg)

### DAW Macro Footswitch Pedal 
I commenced this project to enhance my music composition workflow. As an avid pianist, I love to compose music just as much as I love to perform it. A few years back, I realized that I had difficulty with recording multiple takes in a single recording session. Frustrated by the inefficiencies of the computer keyboard 'shortcuts,' I decided to come up with my own solution to avoid pressing 'spacebar, delete, enter, and R' every time I wanted to re-record a take while composing a song.

To start, I drafted many iterations of the design. I eventually landed on a configuration that utilized the most-used keys when recording a take: spacebar (to stop the current recording), enter (to move the play head back to the start), 'ctrl' and 'z' to be pressed at the same time to undo the recording, and 'r' to record again. I optimized this process with 5 arcade-style buttons and 2 smaller buttons that would be easily pressed in various combinations with a foot. A schematic will be added shortly showing the commands for each key.

In terms of hardware, the main structure is a wedge comprised of 2 pieces of plywood. The angled design enables for a comfortable foot rest while recording. The wiring was done in accordance to the pin-outs of each keyboard controller. Prior to project commencement, a spreadsheet was used to record each corresponding key-out for each pair of pins on each controller. Two controllers were used to accomodate for a faulty controller. USB power was used to power LEDs in the 2 smaller switches, as well as 3 LEDs on the underside of the plywood.

Front                                                              |  Bottom
:-----------------------------------------------------------------:|:-------------------------------------------------:
![DAW_Footswitch 1](/assets/Project_Pictures/DAW_Footswitch1.jpg)  |  ![DAW_Footswitch2](/assets/Project_Pictures/DAW_Footswitch2.jpg)

### Portable Raspberry Pi Synth
This was a project created over the summer of 2019 -  it consists of a Raspberry Pi Zero W, a portable 5V USB battery pack, a USB to 1/8" audio-in and out jack, and LED lighting with a Power switch, all inside a clear plastic enclosure. The Pi is running Raspbian Jesse with an instance of FluidSynth (a software MIDI synthesizer) instantiated on startup. A MIDI keyboard can be plugged in via USB and headphones or a speaker can connect to the audio out jack. This project serves to lighten the load when playing music on the go, or when playing a gig with the MIDI Keytar, as seen below.

![RaspiSynth](/assets/Project_Pictures/RaspiSynth.jpg)

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
I have configured and built many servers over the span of my teenage years. Being into video games such as Minecraft when I was younger, I have always been interested in server configuration - static and dynamic IP addresses, port forwarding and router security. I have revamped Dell PowerEdge T100 and 2950 servers, changing RAM and installing hard drives and SSDs. Using old Lenovo office computers, I have created a personal file storage cloud. Using FreeNAS and multimedia plugins such as Plex Media Server, I've set up movie and music streaming services that may be accessed worldwide through portforwarding and SSH utilities. In addition, I have experimented with Windows Server 2012 and Apple OS X Server (through VMWare's ESXi) for file backup. I am constantly trying to improve my networking knowledge, for example, I used an old Cisco E2500 to test-install DD-WRT software and convert it to a repeater for my home network.

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
This project was created for a highschool computer science course. I led a team to develop a 2D platformer game using object-oriented programming, delegating tasks to individuals and documenting the project in weekly summation journals. To improve project organization, I used IPO charts, pseudocode, and software development lifecycles. Most of what I learned for this project came from YouTube tutorials - the channel 'RealTutsGML' was used as a primary resource. The following pictures show some gameplay.

![WaveGame_1](/assets/Project_Pictures/WaveGame_1.png)

![WaveGame_Boss](/assets/Project_Pictures/WaveGame_Boss.png)

![WaveGame_Lose](/assets/Project_Pictures/WaveGame_Lose.png)

### Java | Inventory Management Software
I developed this application in highschool as well - it takes inputs for item information, and returns stock information in a GUI. 

![InventoryTracker_AddItem](/assets/Project_Pictures/InventoryTracker_AddItem.jpg) ![InventoryTracker_DiscontinueItem](/assets/Project_Pictures/InventoryTracker_DeleteItem.jpg)

### MATLAB | Robot Position Curve Fitting
I have significant experience programming in MATLAB, using scripts for techniques such as vector and matrix operations, numeric and symbolic computation, 2D and 3D graphing, polynomial curve fitting, derivatives, linear systems, and parameterization. Using MATLAB, I imported robot position data and used polynomial curve-fitting techniques to find optimal models for position, velocity and acceleration. Below are some graphs from the final project document.

![MATLAB_RobotGraph_1](/assets/Project_Pictures/MATLAB_RobotGraph_1.png) ![MATLAB_RobotGraph_2](/assets/Project_Pictures/MATLAB_RobotGraph_2.png)

### C/C++ | Chord App/Jazzifier
An app I designed over the summer of 2019 to create pseudo-randomized jazz chord charts for musical inspiration. 

![Jazzifier_Demo](/assets/Project_Pictures/Jazzifier_Demo.png) 



[<Back to Home](./)
