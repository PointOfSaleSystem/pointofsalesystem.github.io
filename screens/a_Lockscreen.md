---
layout: page
title: Lockscreen
permalink: /lockscreen/
---
![Lock Screen](http://i.imgur.com/Zn0Vco1.png)

##What is this screen?
When the PointofSaleSystem application is started, this is the first screen the user sees. This is a form of access control that ensures that no persons other than the designated cashier gains access to the program. 

##How do I use it?
The user has to enter a password to access the application. This is done by clicking on the numbers on the right. If the user made a mistake when entering the password, they can click on the back button to clear the field. 

For demonstration purposes, the password of the application is `0000`. If the password is entered incorrectly, a dialog pane is brought up to display an error message. 

This is not the only function of this screen. Like all of the other screens, when the user clicks on the logo at the top left corner, it takes you to [source code](https://github.com/iggnoreza/PointOfSaleSystem) of the application. 

Another function that this screen has, like all the other screens, is the ablitiy to access the screen's project notes by clicking on the `?` in the top right corner.

The application can be quit by clicking on the `X` in the top right corner.

##Known Bugs
When the user tries to type in a password, unfortunately the user can type a password longer than 4 characters. All passwords for this application are 4 characters long to conform to convention. 

There is also no other way to change the password except for in the code. If you want to change the password, ask the developer to go to `line 17` in the file, and change `private final String masterpass` to your desired 4 digit password. 