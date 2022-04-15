# Workshop #5

![](https://user-images.githubusercontent.com/46844031/163506188-57baccc2-6610-4f39-8429-5ddeb1d8c2f2.gif)

The game requires the player to enter move location commands to reveal what is hidden at a given position along the path. The object of the game is for the player to find as many treasures as possible before running out of moves or lives. Discovering a bomb will reduce the player’s life count. Discovering a treasure will earn the player treasure points. Discovering both, a treasure with a bomb in the same location will reduce the player’s life count and earn the player treasure points (consider it a life insurance payout). Before playing the game, the program will prompt the user to perform some upfront configurations to the player and the game components – these settings will define how the game is played.



````
PLAYER Configuration
--------------------
Enter a single character to represent the player: D
Set the number of lives: 10
Player configuration set-up is complete

GAME Configuration
------------------
Set the path length (a multiple of 5 between 10-70): 25
Set the limit for number of moves allowed: 17
````

To set the bombs you need to type n rows of 1 and 0 where 1 means there are (bomb or treasure) and 0 means empty.

````
BOMB Placement
--------------
Enter the bomb positions in sets of 5 where a value
of 1=BOMB, and 0=NO BOMB. Space-delimit your input.
(Example: 1 0 0 1 1) NOTE: there are 25 to set!
   Positions [ 1- 5]: 1 0 1 0 0
   Positions [ 6-10]: 0 0 0 0 1
   Positions [11-15]: 1 1 0 0 0
   Positions [16-20]: 1 0 0 0 1
   Positions [21-25]: 1 1 1 0 0
BOMB placement set

TREASURE Placement
------------------
Enter the treasure placements in sets of 5 where a value
of 1=TREASURE, and 0=NO TREASURE. Space-delimit your input.
(Example: 1 0 0 1 1) NOTE: there are 25 to set!
   Positions [ 1- 5]: 0 0 0 0 0
   Positions [ 6-10]: 1 0 0 0 1
   Positions [11-15]: 0 0 1 1 0
   Positions [16-20]: 1 0 0 0 0
   Positions [21-25]: 0 0 0 0 1
TREASURE placement set
````

If there is a bomb and a treasure at same number both actions will be count.

````
====================================
~ Get ready to play TREASURE HUNT! ~
====================================

  ▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒
  |||||||||1|||||||||2|||||
  1234567890123456789012345
+---------------------------------------------------+
  Lives: 10  | Treasures:  0  |  Moves Remaining: 17
+---------------------------------------------------+
Next Move [1-25]:
````

You need to select a move and will reveal one of the 4 options:

Explosion:

````
Next Move [1-25]: 1

===============> [!] !!! BOOOOOM !!! [!]

  D
  !▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒
  |||||||||1|||||||||2|||||
````

Empty space:

````
Next Move [1-25]: 2

===============> [.] ...Nothing found here... [.]

   D
  !.▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒
  |||||||||1|||||||||2|||||
````

Treasure:

````
Next Move [1-25]: 25

===============> [$] $$$ Found Treasure! $$$ [$]

                          D
  !.▒▒▒▒▒▒▒&▒▒▒▒▒▒▒▒▒▒▒▒▒▒$
  |||||||||1|||||||||2|||||
````

Bomb + Treasure:

````
Next Move [1-25]: 10

===============> [&] !!! BOOOOOM !!! [&]
===============> [&] $$$ Life Insurance Payout!!! [&]

           D
  !.▒▒▒▒▒▒▒&▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒
  |||||||||1|||||||||2|||||
````

You can not go 2 times at the same place:

````
Next Move [1-25]: 13

===============> Dope! You've been here before!
````

You can get all your treasures and try finishing your movements without losing all your lives.

````
Next Move [1-25]: 19

===============> [.] ...Nothing found here... [.]

                    D
  !.!..$▒▒.&▒▒$$.&▒▒.!!▒!▒$
  |||||||||1|||||||||2|||||
  1234567890123456789012345
+---------------------------------------------------+
  Lives:  3  | Treasures:  6  |  Moves Remaining:  0
+---------------------------------------------------+

##################
#   Game over!   #
##################

You should play again and try to beat your score!
````
