Workshop #4
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
How many wish list items do you want to forecast?: 5 <- Itens in your wish list

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
