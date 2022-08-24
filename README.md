# Humans-vs-Quantum-Computers---IBM
Womanium Quantum Hackathon 2022
# Team GerCam Computing: QLudo (Quantum Ludo) Game (link: https://qludo-30fc6.web.app)
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
- The QLudo Game is an improvement of the classical Ludo game with the addition of Quantum Mechanics that come in the case of the superposition of movements of a player's seed. The QLudo Game is a web game that a player can play realtime on an IBM Quantum computer.

2. github files overview
   - https://github.com/carrington-115/Humans-vs-Quantum-Computers---IBM/blob/main/Play_example.png : this image is a graphical description of what happens during the game.
   - https://github.com/carrington-115/Humans-vs-Quantum-Computers---IBM/blob/main/Qludo_game_by_GerCam_computing-checkpoint.ipynb : this is the jupyter notebook for the quantum circuits
   - https://github.com/carrington-115/Humans-vs-Quantum-Computers---IBM/blob/main/Quantum%20ludo%20game%20ui.pdf : this is a pdf of the UI/UX on figma
   - https://github.com/carrington-115/Humans-vs-Quantum-Computers---IBM/blob/main/README.md this is the readme file
   - https://github.com/carrington-115/Humans-vs-Quantum-Computers---IBM/blob/main/Womanium%20IBM%20Challenge%202022.pdf : this is the ibm challenge file
   - https://github.com/carrington-115/Humans-vs-Quantum-Computers---IBM/blob/main/system_flow.png : this image shows how the computation flows in different parts of the game system.
   - check the game ui on: https://qludo-30fc6.web.app
   
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
![Play_example](https://user-images.githubusercontent.com/103027105/186297992-6d3e7aee-0432-471f-b29e-2325da2ed174.png)

5. Building Tools
- The Game Interface: figma was used to design the UI/UX experience, React.js was use to build this interface, google firebase (pyrebase (python firebase)) is used as the backend responsible for the realtime database optimizations and authentication.
- The Quantum Circuit: qiskit is used to build the quantum circuits of the game and for the simulations on a real IBM quantum computer
below is an image that shows how the tools work together to achieve the game flow.

![system_flow](https://user-images.githubusercontent.com/103027105/186298967-3c636c60-b687-4e0a-b8c2-9458e9f3c5e5.png)


6. Tasks completion
Team GerCam computing achieved the following,
- The user interface
- User Authentication from the UI to the circuitry end.
- half connection for the database, the circuit end and the ui
Here are the tasks remaining for team GerCam computing to accomplish:
- The full connection of the ui-database-ciruit end
- The seed movement on the board.
- The simulation of the game on a quantum computer.

7. Current Product (GerCam computing QLudo Game MVP)
The QLudo Game is a web game that can be played realtime on an IBM Quantum computer. You can access this game with this link https://qludo-30fc6.web.app

8. The team
Note: During the Hackathon we created a team of Seven, but just one person worked on the tasks, the others did not work, so it made the work to go slowly. active member means the person who worked and non-active means the person who we registered as a team, but did not contribute any task.
   - Fru-Mark Carrington Chei (Active member)
   - Job Dontsa (non-Active member)
   - Lesly Tsoptio (non-Active member)
   - Myke Vital Sao (non-Active member)
   - Michael Tintcheu (non-Active member)
   - Verena Bender (non-Active member)
    

