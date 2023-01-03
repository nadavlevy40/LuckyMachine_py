
# Slot Machine



## Overview

This is a implementation of a slot machine game. It has three columns and three rows. The user can enter the number of lines they want to bet on (1-3) and the amount they want to bet on each line ($1-$100). The user's balance is updated based on their winnings after each spin. The game allows the user to play until they run out of money or choose to quit.
## Getting Started

To run the game, clone the repository and run python slot_machine.py from the command line.

## Usage
Follow the prompts in the game to enter your bet and spin the slot machine. The game will show you the results of the spin and update your balance based on any winnings.

## Examples
Here is an example of a run of the game:
```
Enter the numbers of lines to bet on (1-3)? 2
what would you like to bet on each line ? $50
You are betting $50 on 2 lines . Total bet is equal to: $100
Current balance: $100
Spinning...
 |  | 
A | A | A
 |  | 
You won $250! Your new balance is: $350
Enter the numbers of lines to bet on (1-3)? 3
what would you like to bet on each line ? $25
You are betting $25 on 3 lines . Total bet is equal to: $75
Current balance: $350
Spinning...
 |  | 
C | C | C
 |  | 
You won $45! Your new balance is: $395
Enter the numbers of lines to bet on (1-3)? 1
what would you like to bet on each line ? $20
You are betting $20 on 1 lines . Total bet is equal to: $20
Current balance: $395
Spinning...
 |  | 
B | B | D
 |  | 
You lost! Your new balance is: $375

```
## Key Points

* The game has four symbols: "A", "B", "C", and "D"
* The symbol values are as follows: "A": 5, "B": 4, "C": 3, "D": 2
* The game checks for winning lines and calculates winnings based on the symbol values and the user's bet
* The user can deposit more money at any time by choosing the "Deposit" option in the main menu



## Key Programming Elements Used

* Data types (e.g. strings, integers, dictionaries)
* Control structures (e.g. for loops, if statements)
* Functions
* Modules (e.g. random)
* Input/output (e.g. print statements, user input)



