WordRace creates a printable board game.
The game board is a 10x13 grid of hexes or squares filled with letters.
The top and bottom row are red and blue respectively for the players' start home rows.
The players take turns laying down a word starting with a colored cell and playing subsequent letters forming a full word. The program is meant to be run multiple times to create a pad of dozens of PDFs to be printed on heavy stock paper.

The playing tiles to mark played letters can be bought from The Game Crafter:

- https://www.thegamecrafter.com/parts/disc-18mm-x-3mm-fluorescent-red and
- https://www.thegamecrafter.com/parts/disc-18mm-x-3mm-fluorescent-blue



## RULES:
- You must start your word with a letter that is already your color, either because it is on your start home row or because it has your colored tile on it.
- You place a colored tile on each letter in the word you play. You can go in any direction up, down right, left, diagonal. You can spell your word forwards towards your opponents home row or loop back towards your own home row. You CAN reuse letters that are already your color, but you CAN NOT reuse the same cell twice in the new word you are placing.
- If you place a colored tile on an opponents colored tile, you get to keep that cell. Remove the opponents colored tile AND ALL OTHER OPPONENTS TILES that have been severed from the path back to the opponent's home row.
- When you place a tile on your opponents home row you win. Your winning word does not have to end on the opponents home row; If any of your letters land on the opponents home row you win.

Note: It is hard to envision words upside down. Instead of placing the board between the players it might be better for both players to look from the same end.

The tricky part was creating a board that is easy to find interesting long words. Random letter placement made terrible boards where words couldn't be made and unplayable dead ends abounded. A better attempt used English language letter frequencies, but that board was still unsatisfactory. The current board uses the frequency of START letters of English words to place the top and bottom home rows, and uses the frequency of English BIGRAMS (letter pairs) to place letters next to already existing letters. This produced a pretty good board. Finally I run rounds of Simulated Annealing to improve the board greatly, favoring boards that can make longer words.

- [Sample HEX board](hex_grid.pdf)
- [Sample SQUARE board](square_grid.pdf)
