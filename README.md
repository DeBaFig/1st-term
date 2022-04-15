
![WorkshopsBanner](https://user-images.githubusercontent.com/46844031/163504859-cc6fd0e2-85de-41be-ba1c-caaa93289a79.png)

<h1 align="center">SENECA WINTER TERM 2021 - WORKSHOPS</h1>

![GitHub last commit](https://img.shields.io/github/last-commit/DeBaFig/1st-term)


<p>Codes of mt workshops and final project.</p>

<!--ts-->
   * [About](#about)
   * [Branches](#branches)
      * [Workshop #2](#workshop-2)
      * [Workshop #3](#workshop-3)
      * [Workshop #4](#workshop-4)
      * [Workshop #5](#workshop-5)
      * [Workshop #6](#workshop-6)
      * [Final Project](#final-project)
   * [Final Considerations](#final-considerations)
      
<!--te-->


## About
------------

<p>During the IPC144 course at Seneca College I was able to learn and apply principles of computer programming, with an emphasis on problem solving strategies using structured programming techniques. Using C programming language, which is widely used and forms the syntactical basis for object-oriented languages such as C++, C#, and Java, is used to introduce problem analysis, algorithm design, and program implementation.</p>

## Branches
------------

This repository is divaded in branches, each branch has one workshop/project, and a pdf with the especifications of it. You can access the branch clicking at the title:

### [Workshop #2](https://github.com/DeBaFig/1st-term/tree/DeBaFig-Workshop2)
------------

![w2](https://user-images.githubusercontent.com/46844031/163504366-e9dd85ad-9961-469e-8ba5-e3b6f74adc13.gif)

This program calculates the number of toonies, loonies, quarters, dimes, nickels, and pennies required to dispense the amount due and displays the remaining owed with each coin denomination.

```
Change Maker Machine
====================
Enter dollars and cents amount to convert to coins (0 to exit): $ (TYPE HERE THE AMOUNT)
```

Click enter and see the result:

```
Change Maker Machine
====================
Enter dollars and cents amount to convert to coins (0 to exit): $100
Service fee (5.0 percent): 5.00
Balance to dispense: $95.00

$2.00 Toonies  X 47 (remaining: $1.00)
$1.00 Loonies  X 1 (remaining: $0.00)
```
### [Workshop #3](https://github.com/DeBaFig/1st-term/tree/DeBaFig-workshop3)

![w3](https://user-images.githubusercontent.com/46844031/163491541-3ced595a-db79-4fc8-a08b-9c49e4269925.gif)

This program gets the input for a specified number (CONST) of days that records the user’s self-diagnosed “wellness” rating for the morning and evening periods of each day. The application will end with a summary of statistics about the data entered.
How to use:

```
General Well-being Log
======================
Set the year and month for the well-being log (YYYY MM): (TYPE HERE THE YEAR AND MONTH OF THE REGISTER)
```

Click enter and add the rating of your day, you can change how many days it would be asked in the CONST variable at the code top page (at moment it is 3 days).

```
2022-JAN-01
   Morning rating (0.0-5.0): 6 <-- your rate
      ERROR: Rating must be between 0.0 and 5.0 inclusive!
   Morning rating (0.0-5.0): 2
   Evening rating (0.0-5.0): 3

2022-JAN-02
   Morning rating (0.0-5.0): 4
   Evening rating (0.0-5.0): 5

2022-JAN-03
   Morning rating (0.0-5.0): 1
   Evening rating (0.0-5.0): 2
```

Finishing with a summary and the average of the rates:

```
Summary
=======
Morning total rating: 7.000
Evening total rating: 10.000
----------------------------
Overall total rating: 17.000

Average morning rating:  2.3
Average evening rating:  3.3
----------------------------
Average overall rating:  2.8
```

### [Workshop #4](https://github.com/DeBaFig/1st-term/tree/DeBaFig-workshop4)
------------

![w4](https://user-images.githubusercontent.com/46844031/163493459-f35ea07a-0f5e-48ec-9168-98e69e699d02.gif)

The program will ask for the user’s monthly income and then ask for the price and priority of a series of items the user would like to purchase in the future. It will store this information and allow the user to view predictions on how long it will take to save enough money to purchase their wish list items.
How to use:

```
+--------------------------+
+   Wish List Forecaster   |
+--------------------------+

Enter your monthly NET income: $ 1000 <- type the You income
```

**There is a min and max (min: 1000 max 400000)**

```
How many wish list items do you want to forecast?: 5 <- Items in your wish list

Item-1 Details:
   Item cost: $1000 <- do I need to explain?
   How important is it to you? [1=must have, 2=important, 3=want]: 1
   Does this item have financing options? [y/n]: y
```

After there'll be a summary and a menu and you'll be able to see how much money do you need.
 
 ```
 Item Priority Financed        Cost
---- -------- -------- -----------
  1      1        y        1000.00
  2      1        y         500.00
  3      3        n        1500.00
  4      2        n        1700.00
  5      3        y        9000.00
---- -------- -------- -----------
                      $   13700.00

How do you want to forecast your wish list?
 1. All items (no filter)
 2. By priority
 0. Quit/Exit
 
 What priority do you want to filter by? [1-3]: 3

====================================================
Filter:   by priority (3)
Amount:   $10500.00
Forecast: 0 years, 11 months
NOTE: Financing options are available on some items.
      You can likely reduce the estimated months.
====================================================
 ```
 
 
### [Workshop #5](https://github.com/DeBaFig/1st-term/tree/DeBaFig-Workshop5)
------------

![w5](https://user-images.githubusercontent.com/46844031/163506188-57baccc2-6610-4f39-8429-5ddeb1d8c2f2.gif)


### [Workshop #6](https://github.com/DeBaFig/1st-term/tree/DeBaFig-workshop6)
------------

![w6](https://user-images.githubusercontent.com/46844031/163506196-b36d5cb5-bb7b-479f-a0e7-ab06252becfa.gif)


### [Final Project](https://github.com/DeBaFig/1st-term/tree/DeBaFig-finalProject)
------------

![finalProject](https://user-images.githubusercontent.com/46844031/163506202-1355aeb8-a8cd-451a-bd8e-33958e6380a8.gif)

This program create a basic ticketing system, a tracking system for customer reported problems. When a customer has a problem they will phone or email for support. The person handling the support request will create a ticket for the request that contains the details of the problem and the customer contact information so that the customer can be notified when there is a solution. 

````
##########################################################################
Starting Account Ticketing System....
   Loading account data... (5 accounts loaded)
   Loading ticket data...  (0 tickets loaded)
##########################################################################
````

Using the text file in the branch ["accounts.txt"](https://github.com/DeBaFig/1st-term/blob/DeBaFig-finalProject/accounts.txt) you use the ADMIN login.

Divided in Administrator an Customer menu you can create and change (limited by a CONST), in the code tickets an users.
You can see the menu options bellow:

-> Administrator Menu

````
Enter the account#: 11111
User Login    : ADMIN
Password      : admin

AGENT: Admin (11111)
==============================================
Account Ticketing System - Agent Menu
==============================================
 1) Add a new account
 2) Modify an existing account
 3) Remove an account
 4) List accounts: summary view
 5) List accounts: detailed view
----------------------------------------------
 6) List new tickets
 7) List active tickets
 8) List closed tickets
 9) Manage a ticket
10) Archive closed tickets
----------------------------------------------
11) View archived account statistics
12) View archived tickets statistics
----------------------------------------------
0) Logout
````

-> Customer Menu

````
Enter the account#: 82045
User Login    : De
Password      : 12**ooOO

CUSTOMER: Denize (82045)
==============================================
Customer Main Menu
==============================================
1) View your account detail
2) Create a new ticket
3) Modify an active ticket
4) List my tickets
----------------------------------------------
0) Logout
````

This program have implementations to create persistent storage of the account and ticketing data. The system load account and ticket information from files, save account and ticket information to files and finally archive data which will no longer be actively used in the system.

````
Saving session modifications...
   6 account saved.
   1 tickets saved.
### LOGGED OUT ###
````
Modifications made during the session only will be save when the user click on logout.

## Final considerations
------------
