# BattleShip
Battleship game with the game logic implemented on C and a GUI in GTK+.

Compile with:
gcc window.c board.c main.c events.c -o final.o `pkg-config --cflags --libs  gtk+-3.0`

And then: ./final.o
