# Battleship
Game Group Project: Battleship

How to play battleship

Players place their ship on the board. Two different ships can not be touching one another.
Player 1 chooses one place on player 2s board. If the ship player 2 ship is hit, player 1 gets another turn. They will keep going until they hit empty spot.

After the player 1 hits empty spot, player 2 will begin to hit on player 1 board. If ship is hit, then player 2 gets another turn. If empty space is hit, switch back to player 1 turn.

When a player hits all ships on other players board, game is over and that player will win.

if board empty, place ship randomly
else if, place ship in most empty space

Turn 1: if board empty hit any random space

if ship is hit, hit square next to it
    else if square is not correct, try other direction of hit
if ship is two hits in row, continue hit on the same direction until ship is sunk
    else if square is not correct, try other direction of hit
if ship is completely sunk, hit most empty area

