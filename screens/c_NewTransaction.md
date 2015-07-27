---
layout: page
title: New Transaction
permalink: /newtransaction/
---
![New Transaction](http://i.imgur.com/jGjPjHn.png)

##What is this screen?
This screen is where the actual transactions with the customers take place. This function, along with the [search](/search/) function, are the only two functions that are displayed to the customers and to the cashiers - the rest is all done by the manager. 

##How do I use it?
The user can select any of the products in the database from the table to the right, and it will add that product to the left, on the output area. 

Alternatively, the user can click on the `Barcode` tab, and type the specific barcode of an item in the database via a `JOptionPane`, and it will be added to the output window. 

If need be, a store manager can click on the `Manager` tab, enter his password, and enter the barcode of a product that needs to be removed from the transaction.

For demonstration purposes, the manager password is `1234` but can be changed to any string in the `NewTransactionGUI.java` file in `line 22`. If the password is entered incorrectly, a dialog pane is brought up to display an error message. 

Like all of the other screens, when the user clicks on the logo at the top left corner, it takes you to the [source code](https://github.com/iggnoreza/PointOfSaleSystem) of the application. 

A back button is supplied at the top of the screen to return to the home screen whenever the user wants to.

Another function that this screen has, like all the other screens, is the ablitiy to access the screen's project notes by clicking on the `?` in the top right corner.

##Known Bugs
For the time being, the cashier has to enter the product barcodes with the keyboard. In the future, the cashier might be able to use a barcode scanner to add and remove the items from the transaction!