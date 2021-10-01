# RISK GAME

![map](https://user-images.githubusercontent.com/49976598/135637978-beaccadb-0e6b-4cce-9f90-772da8faa8c6.jpg)

## Game Description 
Risk is a strategic board game involving diplomacy, conflict and conquest of more than two players.
It is played on a chessboard depicting the political map of the world,
Divided into several territories. Take turns among players who control the army of chess pieces
They try to seize territory from other players, and the result is determined by rolling the dice.
Players can form and dissolve alliances during the game.
The goal of the game is to occupy every territory on the board and eliminate other players in the process.


## Development
This is an Android application which enables users to play RISK GAME.
My main contributions are:
1. Designed and implemented the backend game server and chat server via Non-blocking IO and state machine.
2. Handled concurrency requests with multi-thread programming from multiple users.
3. Realized server-client communication with TCP socket programming. 
4. Used Hibernate to store game states to Postgres database to make sure that users can go back to the game after any shutdown.


## Other Info
### Evolution3 Unit Type Transfer Feature
https://docs.google.com/document/d/1P9i6wgl7DS_BDTSVlzvQ1whGcxe-0AHW_vA2KxTKXNk/edit

### UX prototype
https://docs.google.com/presentation/d/176PTTRUj4xIX26alagKeaRLKd9goiVSM8KMmkJsWLHA/edit?usp=sharing

### UML Diagram
https://www.processon.com/view/link/606d22bd5653bb5cea06e929

### New feature Description
https://docs.google.com/document/d/1P9i6wgl7DS_BDTSVlzvQ1whGcxe-0AHW_vA2KxTKXNk/edit?usp=sharing

### Coverage
[Detailed coverage](https://xs75.pages.oit.duke.edu/ece651-group4-project1/dashboard.html)
