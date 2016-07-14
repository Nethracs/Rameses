
#Rameses

Rameses is a two player nxn board game.It has nx n grids and n^2 pebbles for two players. Initially the board starts empty and all pebbles are in a pile beside the board. Player 1 picks up a pebble and
places it in any square of the grid. Player 2 then picks up a pebble from the pile, and places it in any open square (i.e. any square except the one selected by Player 1). Play continues back and forth, 
with each player picking up a pebble from the pile and placing it in any open square. A player loses the game as soon as they place a pebble that completes a row, a column, or one of the two diagonals of
the board, and then the other player wins.

#Algorithm

Step1:Take input n from command and build NxN matrix  
Step2:check the matrix element if it is filled,if filled skip else compute the heuristic by calling sum()  
step3:Call col() to function to compute number of empty spaces on filling the position,likewise call row() and diagonal d()  
step4:compute heuristic for all position and choose the position with maximum value of col and row and which doesn't affect diagonal else maximum diagonal value  
step5:output the favourable position  
step6:Exit on filling the row,column and diagonal and print Exit message Game over  


#steps to run the code

Input format, for a 3X3 grid,

**python rameses.py 3 .x......x 5**

where n is 3  
.x......x is the element order in row  
5 is the next position where the element should be placed



