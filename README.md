# CompSciPrograms
                                     
# ReadMe for COMP 15 HW6
## Boggle Assignment
Winnona DeSombre - COMP 15- Professor Chris Gregg

1.  Program Purpose: To create a boggle program that reads in the board and 
   a dictionary, solves all possible words within the board
   by cross referencing with said dictionary, and checks scores
   against words written by the user who plays the boggle game.

----------------------------------------------------------------------------

Files & Programs:

 a) BogSolver - Solving for all possible words within the boggle board.
   BogWordList.h: Declaration of a BogWordList Class:
               Data Structures:
                    BogWordList class: a vector of BogWords.
                    BogWord: a vector of BogLetts.
                    BogLett: a struct holding a character and the coordinates
                            of that character within the boggle board.

  Dictionary.h & cpp: Declaration & Implementation of a Dictionary already made.
  
  BogSolver.h: Declaration of a BogSolver Class:
                Data Structures:
                  Dictionary: a trie of words given to the program
                  2D Vector of Characters: "vector<vector<char> >" to represent
                  our board.
                  BogWordList: See above.

