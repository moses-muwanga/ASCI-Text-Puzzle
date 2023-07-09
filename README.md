# ASCI-Text-Puzzle

### What is ASCII?
American Standard Code for Information Interchange (ASCII). ASCII technically refers to the encoding of text as integers, but often the term ASCII is used to refer to text-based things, e.g. ASCII drawings.

### Project Description
This is an interactive ASCII character code-based game using python which implements file IO to read and load .txt files containing game levels into the program, and recursion to update the game board based on user inputs.

The game progresses in 5 levels, each with a unique game board loaded from a file. The game board is a 2D list of symbols (strings) from the set {'&', '@', '#', '%'}. The goal of the game is to make all of the symbols on the board the same in the fewest possible moves.

The player's moves consist of picking a symbol and a location on the board. Then, that location and all contiguous symbols (ie. matching symbols in adjacent locations) are changed to the user's selected symbol.

After each level, the number of moves to solve that level is displayed as well as the completed board, then next level begins. After 5 levels, the total number of moves the player used for the whole game  is displayed and they are prompted to play again or quit the program.
