# Tic Tac Toe Game Implemented in java - multiplayer
## About the game

It's a program to run a two player tic tac toe game.

It contains a game server that listens to the connections of clients, as well as a game client program. 

The clients will be able to play each other over the network through the server.

This game uses TCP to pass information between server and client.

First player to connect goes first.

----

#How to run the game?
----
open a terminal and run the following commands

`$ cd Game`

   ` $ javac *.java`

   ` $ java GameServer`

now you have run the server, open another two terminals that will work as two clients (player 1, player2) and run the next command 

   ` $ java GameClient`

----

