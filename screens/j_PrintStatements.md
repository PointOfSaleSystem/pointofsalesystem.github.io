---
layout: page
title: Print Statements
permalink: /printstatements/
---
![Print Statements](http://i.imgur.com/8e3m5eA.png)

##What is this screen?
A manager user can use this screen to view the net profit for a specified time period. This is one of the easier screens to use, and the process of picking dates have been made even easier with the help of Java's `JXDatePicker` object. 

##How do I use it?
The user selects two dates from the `JXDatePickers` - a `Start Date` and an `End Date`. The moment the `End Date` has been selected, the application calculates the `Total Income`, `Total Expenses` and then subtracts the two from each other to calculate the `Profit` field. 

The `Total Income` and `Total Expenses` is calculated by generating a `SQL` statement that returns all the `Transactions` and `Orders` for the specified time period. The `TotalCost_NoVAT` field in the `Transactions` table is used to calculate the `Total Income`, while the `Order_Price` field in the `Orders` table is used to calculate the `Total Expenses`. 

Once the two dates have been selected, the user can either click on the `Export to text file` button or on the `Send as Email` button. The `Export to text file` button saves every single `Transaction` and `Order` in the specified time period to a text file name `IncomeStatement<Today'sDate>`.

##Known Bugs
The `JTextFields` are only updated once the `End Date` has been changed. This means that if the user would like to view the `Profit` for a different time period, both the `Start Date` and `End Date` have to be changed. Even if it's for the same `End Date`, simply change the `End Date` to a random date and then back to the specific date you would like to use.
