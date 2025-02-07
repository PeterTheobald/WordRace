WordRace creates a printable board game.
The game board is a 10x13 grid of hexes or squares filled with letters.
The top and bottom row are red and blue respectively for the players' start home rows.
The players take turns laying down a word starting with a colored cell and playing subsequent letters forming a full word. The program is meant to be run multiple times to create a pad of dozens of PDFs to be printed on heavy stock paper.

The playing tiles to mark played letters can be bought from The Game Crafter:

- https://www.thegamecrafter.com/parts/disc-18mm-x-3mm-fluorescent-red and
- https://www.thegamecrafter.com/parts/disc-18mm-x-3mm-fluorescent-blue

The tricky part was creating a board that is easy to find interesting long words. Random letter placement made terrible boards where words couldn't be made and unplayable dead ends abounded. A better attempt used English language letter frequencies, but that board was still unsatisfactory. The current board uses the frequency of START letters of English words to place the top and bottom home rows, and uses the frequency of English BIGRAMS (letter pairs) to place letters next to already existing letters. This produced a pretty good board. Finally I run rounds of Simulated Annealing to improve the board greatly, favoring boards that can make longer words.

- [Sample HEX board](hex_grid.pdf)
- [Sample SQUARE board](square_grid.pdf)
