# Hangman-Game
INTRODUCTION
It is a python-based word-oriented game in which a player tries to guess one letter at a time which will form a word which will be related with the hint provided in it. For any wrong attempt an animated man will be created which seems to be getting hanged and it gets complete after all the wrong guesses. On the other hand, a correct guess of letters it will automatically gets placed on its own place and as the player guesses all letters correctly he will be declared as winner.
This project has one player and two player options. In one player the player will be provided with letters which are already stored in the database and in two player one player will provide his own word along with a hint and the other one has to guess it.

SYSTEM IMPLEMENTATION 
•	Modules
it consists of 5 modules and each module is interrelated with another one and they compiles the complete system.




Module-1 :- project.py

This module helps in generating a welcome screen and along with that it allows user start his game or exit the game.

Module-2 :- page1.py

This module allows the user to choose the type of game he wants to play. This module gave the option of single player and two players.

Module-3 :- page2.py
This module generates the main game screen. Here the player will get a screen where he will guess a word with the help of the hint and there will be a keyboard provided through which he can give his input. If the guess is incorrect it will generate a figure which will be the HANGMAN.

Module-4 :-page3.py
This module is linked with the module no 2. When the player will choose two player game option this will come in work. Here one of those player can provide a word and the hint related with that word and the other one will guess that.
