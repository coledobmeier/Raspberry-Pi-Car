# Raspberry Pi remote controlled car
This project served as a colleague and I's final project for our semester of learning Python Programming and how to use Raspberry Pi's. We utilized our Raspberry Pi's, Parts from a Jetson Nano car kit, and python programming to create this machine. It is controlled using a wired NES controller that takes input through some of Pygame's built in functions. We first wrote scripts to figure out what 'buttons' the controller had, and then we took the data from that to make a program that moved the square in a digital window in accordance with the controller input. This project was overall very successful and a valuable learning experience of how to integrate very different components in 

### 1. The Idea
- Originally the idea behind this project was to create the Sandcrawler from Star Wars. However, due to lack of lego parts and more Jetson nano motors, we created this RC car. The big challenge on this project was connecting the motors to the NES Controller. The motors were designed to integrate with a Jetson Nano, which operated differently than the Raspberry Pi. After reading much documentation, and using pygame, we had our first successful [motor test](https://github.com/cole-dobmeier/Raspberry-Pi-Car/blob/main/Testing_Video.mp4)
- Within this video, you can see the terminal reading back our left and right motor speeds, as well as when using the D-Pad to turn, the respective wheels slow down to facilitate smooth turning.
---
After implementing this Script and fulling putting together our car, we were ready for our first test drive. This [demonstration](https://github.com/cole-dobmeier/Raspberry-Pi-Car/blob/main/Demonstration_Video.mp4) was successful and we were ready to present our car to our peers.

### TechNologies:
- Python Programming
- Differential wheel speed while turning
- Pygame controller functions
- Jetson Nano car kits

### Features:
- NES Easy-Controllability controller
- Adjustable speeds
- 360 degree operation
