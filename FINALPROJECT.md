
**ZELAM Final Project for CSC 2463 Documentation**

**Welcome to Oswald's Flying Adventures! Help Oswald the Flying Pig navigate the sky and collect cotton candy.  Avoid pesky thunderstorm clouds because every time he hits one, he moves faster.  
The player has 30 seconds to collect as much cotton candy as possible.  Oswald moves up and down via a joystick connected to an Arduino. He is set to a costant speed. Every time he hits a piece of cotton candy, a buzzer goes off.  The music will speed up during the last 10 seconds of the game.**

**Graphics:**
Oswald, the cotton candy, and the thundercloud were drawn by Zoe Elam using the Autodesk Sketchbook app on an iPad.  The images were traced onto the placement of a pre-existing spritesheet to make finding sprite positions easier.
![Oswald   CC - Copy](https://user-images.githubusercontent.com/97987830/164994747-47dbfd6c-8324-48a1-8f80-3f90cbae14d8.png)
![Thunder(1)](https://user-images.githubusercontent.com/97987830/164995063-18351409-7843-4a44-b841-5c3ae091cbe0.png)

**Sounds:**
The background music was provided from Freesound. [https://freesound.org/people/Mrthenoronha/sounds/513427/](https://freesound.org/people/Mrthenoronha/sounds/513427/)

The cotton candy and thunder sounds were generated using sfxr.  
All sound files can be found below in the ZIP files.
The background music plays when the game begins.  When a cotton candy or a thundercloud is hit, different sounds play.


**Physical Computing:**
The button is connect to ground (black) and digital pin 9 (orange).
The joystick controller is connected to GND (black), 5V (white), A0 (purple), A1 (tan), and digital pin 4 (green).  The buzzer plays whenever the button is pressed to signal the start of the game.  The joystick controls Oswald's movements on the screen.
![IMG_2902](https://user-images.githubusercontent.com/97987830/166120741-fafa26d9-8421-4c6a-9cc4-7a118711675f.jpg)


**Video:** [https://youtu.be/SdxQvKJNtso](https://youtu.be/SdxQvKJNtso)

**Future Developments:**
In the future, I would like to implement a pause function that stops the game whenever a thundercloud is hit.  The game would then start back up at a faster speed than before.  I feel like this would give the game an overall better look.  I would also add more obstacles in the sky that Oswald would have to avoid, like flying garbage that stops his movements. Another mode to the game would be to have multiple characters flying in the sky at once.

**Final Code ZIP File:**
[ZELAM_Final_Project.zip](https://github.com/zelam1/zelam1.github.io/files/8656606/ZELAM_Final_Project.zip)
