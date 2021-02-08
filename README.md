# The Project

This project is a cover system mechanic made with Unreal Engine blueprints, with a character that take cover from an obstacle and walk during the cover action.

![](https://github.com/KaykyDeSouzaDias/Cover-System-Unreal-Blueprint/blob/main/Images%20and%20GIFs/CoverSystem_GameplayGIF.gif)

# Reference

My two biggest references were the AAA franchise Gears of War and The Division, which uses this system a lot.

![](https://github.com/KaykyDeSouzaDias/Cover-System-Unreal-Blueprint/blob/main/Images%20and%20GIFs/CoverSystemGIF_Example.gif)

# Objective
This functionality was made for my portfolio and to grow my programming skills.

Also, if you want to use this project for study, make money, etc., it's okay! Use it as you wish!

# How was done?

1.0 - Firstly, I made my cover object, collision boxes, and the cover arrow, all this in one blueprint to be easier.

![](https://github.com/KaykyDeSouzaDias/Cover-System-Unreal-Blueprint/blob/main/Images%20and%20GIFs/IMG06.JPG)

  1.1 - After that, I made a cover interface to pick up some values.
  
  ![](https://github.com/KaykyDeSouzaDias/Cover-System-Unreal-Blueprint/blob/main/Images%20and%20GIFs/IMG01.JPG)
  
  ![](https://github.com/KaykyDeSouzaDias/Cover-System-Unreal-Blueprint/blob/main/Images%20and%20GIFs/IMG02.JPG)
  
  1.1.1 - Notice that I made two functions. And each of them has two variables. The first (CoverIsAvailable) has the values of the CoverRotation and if the cover is available. The second one (StopMove_Cover) is about when the character stop moving during the cover action, those variables are about the directions (Right and Left).
  
  1.3 - And then I distributed the values in the Event Graph.
  
  ![](https://github.com/KaykyDeSouzaDias/Cover-System-Unreal-Blueprint/blob/main/Images%20and%20GIFs/IMG03.JPG)
  
  ![](https://github.com/KaykyDeSouzaDias/Cover-System-Unreal-Blueprint/blob/main/Images%20and%20GIFs/IMG04.JPG)
  
  ![](https://github.com/KaykyDeSouzaDias/Cover-System-Unreal-Blueprint/blob/main/Images%20and%20GIFs/IMG05.JPG)

2.0 - So, I made the cover logic inside the character and configured some buttons, to enter and exit for the cover action. And used the controller rotation yaw to improve the experience and to facilitate.

![](https://github.com/KaykyDeSouzaDias/Cover-System-Unreal-Blueprint/blob/main/Images%20and%20GIFs/IMG07.JPG)

![](https://github.com/KaykyDeSouzaDias/Cover-System-Unreal-Blueprint/blob/main/Images%20and%20GIFs/IMG08.JPG)

![](https://github.com/KaykyDeSouzaDias/Cover-System-Unreal-Blueprint/blob/main/Images%20and%20GIFs/IMG09.JPG)

3.0 - And then, I made a collision border to the character don't go away and stop.

![](https://github.com/KaykyDeSouzaDias/Cover-System-Unreal-Blueprint/blob/main/Images%20and%20GIFs/IMG10.JPG)

![](https://github.com/KaykyDeSouzaDias/Cover-System-Unreal-Blueprint/blob/main/Images%20and%20GIFs/IMG11.JPG)

![](https://github.com/KaykyDeSouzaDias/Cover-System-Unreal-Blueprint/blob/main/Images%20and%20GIFs/IMG12.JPG)

![](https://github.com/KaykyDeSouzaDias/Cover-System-Unreal-Blueprint/blob/main/Images%20and%20GIFs/IMG13.JPG)

![](https://github.com/KaykyDeSouzaDias/Cover-System-Unreal-Blueprint/blob/main/Images%20and%20GIFs/IMG14.JPG)

4.0 - For the finish, I opened the Anim Graph and started to pick up the values of when the character needs to stop, or when he exited or started the cover action, etc. In addition to configuring the animations.

![](https://github.com/KaykyDeSouzaDias/Cover-System-Unreal-Blueprint/blob/main/Images%20and%20GIFs/IMG15.JPG)

![](https://github.com/KaykyDeSouzaDias/Cover-System-Unreal-Blueprint/blob/main/Images%20and%20GIFs/IMG16.JPG)

# That's it! Thank you so much for staying here until the end, and if wanna see more about the project, you can download it!
