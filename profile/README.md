# PC Remote  

## Overview 
We’re building an app that would allow the user to control their 
computer’s mouse on their phone. This app will be built using React 
Native, and will allow a user to either use a phone’s motion sensors or 
touch screen to control the mouse.  

## Specifications
An app that uses the phone touch screen or gyroscope to generate movement 
data, a system that quickly sends the movement data over Wi-Fi to a 
listening PC, as well as a PC program that consumes the phone input, and 
generates cursor movement based on the input. 
Finally, an Aim-Labs like mini game mode in the PC program that tests a 
users ability to accurately click randomly generated points on the PC 
screen.  

## Goals
- Creating a multi platform App to control PC cursor via mobile device.  
- Create a comprehensive testing suite to verify that App data is properly 
being processed by the PC  
-  Create a mini game to allow prospective users to demo the app and see 
its usefulness.


## Milestones  
- [x] PC demo  
  - Creating a desktop program to move the cursor using a keyboard, as 
well as displays the coordinates of a mouse click.  

- [x] Phone Demo  
  - App that does nothing but display gyroscope data, as well touch screen 
heat zones  
  
- [x] Phone-PC Communication  
  - Create functionality that allows for a constant stream of data between 
a phone and PC  


- [ ] Phone-PC Calibration  
  - Create functions that use a sensitivity parameter to allow gyroscope 
data to smoothly translate to mouse movement, in a user-friendly manner  

- [ ] Testing  
  - Using an automated script(s) to generate sample gyroscope data, which 
then verifies PC functionality


## Members  
- [Precious Oyetunji](https://github.com/Kyu)  
- [Raph Mwanza](https://github.com/raphmwanza)
- [Krishant Rauniyar](https://github.com/krishant624)
- [Ethan Jellison](https://github.com/ethanjelli)  

