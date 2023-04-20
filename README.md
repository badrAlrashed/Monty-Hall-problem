# Monty-Hall-problem
comparing my solation to an AI (Microsoft Bing) in creating a mini simulation for the Monty Hall problem.

The Monty Hall problem:
In this problem, you are on a game show and are asked to choose between three doors. Behind each door, there is either a car or a goat. You choose a door. The host, Monty Hall, who knows what’s behind the doors, opens one of the other doors which has a goat behind it. He then asks whether you would like to switch your choice of door to the other remaining door2.

i first created a Mini Sumlation to test which option is better (always switching or sticking to first Choice).

then i provided prompt to AI (Microsoft Bing): write a simulation in python for the monty hall problem that attempt 100 time for switching door everytime and another code for never switching the result of the code should be a precetage of guessing right.

which result in Microsoft Bing Simulation to Monty Hall problem 100 times.

AI (Microsoft Bing) explanation to the code (prompt:Can you explain how this code works?):

Sure! This code simulates the Monty Hall problem 100 times for both switching and not switching the door. The monty_hall function takes a boolean argument switch which determines whether the player switches their door choice or not. The function first randomly chooses which door has the car behind it and which door the player initially chooses. Then, one of the remaining doors is revealed to have a goat behind it. If the player decides to switch their choice, they choose the remaining door that was not revealed and was not their initial choice. If they do not switch, they stick with their initial choice. The function returns True if the player’s final choice is the door with the car behind it and False otherwise.

The simulate function takes a boolean argument switch and runs the monty_hall function 100 times with that argument. It counts the number of times the player wins (i.e., the monty_hall function returns True) and returns the percentage of wins.

The code then calls the simulate function twice, once with switch=True and once with switch=False, to get the winning percentages for both cases and prints them out.

I hope this helps! Is there anything else you would like to know?

