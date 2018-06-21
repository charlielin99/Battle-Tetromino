# Battle Tetromino

Battle Tetromino is a spin on the classic Tetris game where various powerups can be employed to wreck havoc on the opponent's game board.

<img src="https://github.com/charlielin99/Battle-Tetromino/blob/master/Login.png?raw=true" height="210px"></img></br>

Features:
1. Local Player vs Player
2. Local Player vs Machine 
3. Online Multiplayer and Chatroom
4. Machine vs Machine

## Genetic Algorithm
The machine modes were trained with ~ 30 generations using a **genetic algorithm** which assessed children from generation x with a fitness function and mutation operator using **supervised heuristic optimization**.

<img src="https://github.com/charlielin99/Battle-Tetromino/blob/master/MachineAlgo.png" height="420px"></img></br>
<sup>_Machine Algorithm after 24 hours: reached score of 61,000,000 and cleared 7000 lines_</sup>

## Websocket Multiplayer
Used a **low-latency message queue optimization** on the websocket connection to eliminate 95% of game play delays
