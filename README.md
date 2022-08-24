# Humans-vs-Quantum-Computers---IBM
Womanium Quantum Hackathon 2022
# Team GerCam Computing: QLudo (Quantum Ludo) Game
# Table of Contents
- Introduction 
- github files overview
- Overview of Quantum Mechanics in QLudo
- Rules of the Game
- Tools used to build the Game
- Task completion
- Current Product
- Team

1. Introduction
- The QLudo Game is an improvement of the classical Ludo game with the addition of Quantum Mechanics that come in the case of the superposition of movements of a player's seed.

2. github files overview
3. Overview of Quantum Mechanics in QLudo
- Superposition: The Superposition of the movements of the game means the moves of the player's seed on the board is not fixed, it is superposed. This is achieved in the game by applying a Hadamard gate to the qubit of the first player
- Entanglement: The game enters a state of entanglement when both players have chosen their move on the board and played. This entanglement then causes the collapse of the game. During the game, entanglement is achieved by applying a controlled not gate where the first player qubit is the control qubit and player's opponent qubit is the target qubit.
- Collapse: During the collapse, suppose the player chosed to take a quantum move of his seed, then the final move of the seed for that round will be revealed based on the measurement done.

4. Rules of the Game (Note: the game is player on a user interface: https://qludo-30fc6.web.app)
- The game starts with the player oblaged to take a classical move to achieve a spin of 6 to remove a seed to the board.
- The game continues with the player chosing the type of move to take (quantum or classical) on subsequent rounds
- When the move is taken, the player spins the dice based on the move that the player took
- A notification is sent to the UI notifying the player that their move was successful giving the opponent the opportunity to play.
- The opponent (the computer) choses the type of move that the same thing is done.
- Then, the board collapses to one state and the player has the opportunity to chose the seed to apply the move.
- The first player to send all their seeds to their homes is the winner of the game
