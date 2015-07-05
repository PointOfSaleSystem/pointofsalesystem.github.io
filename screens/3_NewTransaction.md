---
layout: page
title: New Transaction
permalink: /newtransaction/
---
![New Transaction](/assets/NewTransaction.png)

##What is this screen?
This screen is where the actual transactions with the customers take place. This function, along with the [search](/search/) function, are the only two functions that are displayed to the customers and to the cashiers - the rest is all done by the manager. 

##How do I use it?
The user can select any of the products in the database from the table to the right, and it will add that product to the left, on the output area. 

Alternatively, the user can click on the `Keypad` tab, and [type in](/assets/NewTransactionGUI_Keypad.png) the specific barcode of an item in the database, and it will be added to the output window. 

If need be, a store manager can click on the `Manager` tab, enter his [password](https://raw.githubusercontent.com/PointOfSaleSystem/pointofsalesystem.github.io/master/assets/ManagerPassword.PNG) and [enter the barcode](/assets/NewTransactionGUI_Manager.png) of a product that needs to be removed from the transaction.

For demonstration purposes, the manager password is `1234` but can be changed to any string in the `NewTransactionGUI.java` file in `line 22`. If the password is entered incorrectly, a dialog pane is brought up to display an error message. 

Like all of the other screens, when the user clicks on the logo at the top left corner, it takes you to [source code](https://github.com/iggnoreza/PointOfSaleSystem) of the application. 

A back button is supplied at the top of the screen to return to the home screen whenever the user wants to.

Another function that this screen has, like all the other screens, is the ablitiy to access the screen's project notes by clicking on the screen title at the top next to the POS logo.

##Known Bugs
I am currently struggling with the functionality of the `Keypad` and `Manager` buttons. They are supposed to display their own text fields and icons etc. Unfortunately, I have not yet found a way  to hide all the other tabs' content. 