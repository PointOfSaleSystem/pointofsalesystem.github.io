---
layout: page
title: Home
permalink: /home/
---
![Home](http://i.imgur.com/a7pTZaX.jpg)

##What is this screen?
When the lockscreen password is successfully entered the user is brought to this screen. This is where the user can access the three main aspects of the application, namely: 

1. [New Transaction](/newtransaction/)
2. [Search](/search/)
3. [Manager Portal](/managerportal/)


##How do I use it?
Like the other screens, the user can click on the `POS` logo at the top left to view the application [source code](https://github.com/iggnoreza/PointOfSaleSystem), click on the screen title (Home) to open up these project notes, and quit the program with the `X` button in the top right corner. Unlike the lockscreen there is also a lock button which let's you lock the program while you are away.

The user can also click on the Spar logo to redirect them to [their site](http://kwiksparpaulroos.co.za/).

When the user clicks on the `Manager Portal` button, a dialog pane is brought up to enter the manager password. For the time being, the manager password is `1234`, and can only be changed by going to the `HomeGUI.java` file in `line 20` and changing `private final String managerPass` to your desired pass.

##Known Bugs
When the dialog is brought up to type in the `Manager Password`, the password that the manager enters can be seen by anyone standing near the screen. Unlike the lockscreen, a `*` isn't displayed whenever a user enters a character, but rather the specific character that is being entered. This is a big security flaw and still has to be figured out. The password is also not limited to digits, but it can be any string of characters, of any length.  
