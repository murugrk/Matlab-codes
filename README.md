# Matlab-codes



we study some numerical aspects of the classical two-player game
rock-paper-scissors, using MATLAB. In particular, we focus on simple strategies that, in
the long run, could benefit both the computer and the human player.
The provided files are:
 game.fig contains the graphical user interface and should not be modified
 game.m contains the initialization of the game and the rest of the logic (e.g. handling
events) related to the GUI. 
 mchoice.m contains the "brain" of the game. ( the main alogirthm implementation is here)
 gen human move.m is a function that generates moves for the human player. It can
be used to run a user-defned number of rounds automatically. 
The GUI contains a button Save data that permits you to create a .mat file containing
the last transition matrix of the game and the results after each round.
