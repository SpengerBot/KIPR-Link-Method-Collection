KIPR-Link-Method-Collection
===========================

Method Collection for the [KIPR Link Controller](http://www.kipr.org/products/link).
 - [Better wait_for_light Method](./wait_for_light.c) which double checks the light. 
     Does not Start when flashlight appears.
     [Source](https://github.com/kipr/libkovan/blob/master/src/botball_c.cpp "kipr/libkovan")
 - [New Drive Methods](./create_drive.c) for the [iRobot Create](http://www.irobot.com/us/learn/Educators/Create.aspx)
    + Drive for a specific Distance (asynchronous and synchronous (Link waits for action finished))
    + Rotate for specific Angle (asynchronous and synchronous (Link waits for action finished))
