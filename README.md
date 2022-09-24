## Project ObSEC - Occupancy based Smart Electronic Control

### Designed and developed by
- [Aswin Sreekumar](https://github.com/aswin-sreekumar)
- [Harini Sabapathy](https://github.com/HariniSabapathy0212)
- [Subiksha T V](https://github.com/SubikshaTV)

### Contents
- [Problem statement](#problem-statement)
- [Proposed solution](#proposed-solution)
- [Features](#features)
- [Flowchart](#flowchart)  
- [Gallery](#gallery)

## Problem statement
Efficient utilization of the limited available energy in developing countries is a practical solution to the present challenges faced in the power sector in the region. Automation of lighting systems in both residential and industrial buildings is one of the strategies for energy efficiency towards a sustainable economic development. Additonal to this, an intelligent universal system that can drive electrical systems based on user presense can help in making electrical appliances autonomous and can save power based on scale of usage. This can include complete or partial shutdown of electical systems at a workspace when inactive.

## Proposed solution
We propose a vision based intelligent system that can detect presence of people in particlar sections of the same arena or workspace and power ON or OFF electrical systems such as lights and fans automatically. For example, controlling the lights and fans inside a classroom when not required or when its partially filled. 


The project consists of a set of ESP32 CAMs placed based on arena that captures and transmits images at discrete intervals of time to the main processing server, a Raspberry Pi. The ESP32 CAMs and the Raspberry Pi are connected over a LAN for wireless communication. The Pi performs Image Processing on the received images to compute occupied and unoccupied areas and accordingly drives the relays to the respective lights and fans.


This design can be easily scaled up based on application workspace by adding more ESPCAMs into the network, using the same Pi server.

## Features
- Vision based system with wireless image transmission.
- Autonomous and intelligent system.
- Easily scalable based on workspace.
- Power efficient.
- Easily customisable to target arena.
- Decentralised camera approach
- Directly deployable.

## Flowchart
### Sub-systems of project
![flowwchart_iot](https://user-images.githubusercontent.com/63254914/171643414-c75973a5-85d5-40e3-8c01-0d4cf02ad6c3.png)

### Working flowchart
![Untitled Diagram (1)](https://user-images.githubusercontent.com/63254914/171643360-c63cd253-a95a-4949-8149-4c28c31cc60f.png)

## Gallery
### Fabricated ESP32-CAM module
![20220327_194451](https://user-images.githubusercontent.com/63254914/171642063-b7c72d78-941d-4a52-ad28-01a8b52e0bee.jpg)

### Fabricated level shifter
![20220401_201120](https://user-images.githubusercontent.com/63254914/171642117-ac84ac6e-d81c-4540-ac84-cd90be775548.jpg)
![unnamed](https://user-images.githubusercontent.com/63254914/171643459-eee48e23-7951-4398-b3da-6e4e64ef794c.jpg)
