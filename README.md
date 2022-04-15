# Workshop #3

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
