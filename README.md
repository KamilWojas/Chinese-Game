# Chinese-Game

Implement a fully functional game starting with the selection of the number of players, then the game itself (according to the described rules) assuming that after drawing the number of spots on the dice, the player will decide which pawn he will move.

A numerical value should be given as the field number, assuming that the "start" field with the number 0 is located in the upper right corner of the board - as shown in Figure 1. Include the display of auxiliary field numbers for the next full tens to make it easier for players to determine the numbers of the fields on which their pawns are currently located.

The game can be started in one of two ways: 
• by calling the start() method without any parameters, in which case the game will start by randomly indicating which of the players will lead the first pawn; 
• as a form of continuation of the previous game by calling the start(int,int[] [], int[], int[]) in which the following parameters describe: 
– number of players; 
– pawn color (in column 0) and pawn position (in column 1); 
– results table of subsequent draws; 
– decision table 
- describing which the pawn must be moved;

