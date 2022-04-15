# Final Project
------------

![finalProject](https://user-images.githubusercontent.com/46844031/163506202-1355aeb8-a8cd-451a-bd8e-33958e6380a8.gif)

This program creates a basic ticketing system, a tracking system for customer-reported problems. When a customer has a problem they will phone or email for support. The person handling the support request will create a ticket for the request that contains the details of the problem and the customer's contact information so that the customer can be notified when there is a solution. 

````
##########################################################################
Starting Account Ticketing System....
   Loading account data... (5 accounts loaded)
   Loading ticket data...  (0 tickets loaded)
##########################################################################
````

Using the text file in the branch ["accounts.txt"](https://github.com/DeBaFig/1st-term/blob/DeBaFig-finalProject/accounts.txt) you use the ADMIN login.

Divided between the Administrator and Customer menu you can create and change tickets and users (limited by a CONST on code).
You can see the menu options below:

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

This program has implementations to create persistent storage of the account and ticketing data. The system load account and ticket information from files, save account and ticket information to files, and finally archive data that will no longer be actively used in the system.

````
Saving session modifications...
   6 account saved.
   1 tickets saved.
### LOGGED OUT ###
````
Modifications made during the session only will be save when the user click on logout.
