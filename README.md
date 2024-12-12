The goal of this project is to use an FPGA to create an exciting and dynamic racing game for
cars. The game will be fast-paced and real-time, requiring the user to make quick decisions and
react visually.

This is a 2-player game. Each player's car is at the bottom of the screen, and the game takes
place on a three-lane road. The player must move their car to the left or right to avoid collisions
as randomly generated obstacles fall from the top of the screen.

Obstacles will be created at random throughout the three lanes to guarantee a difficult gameplay
experience, with at least one lane always being clear. The player's vehicle, obstacles, and lives
will all be shown in the game's straightforward but eye-catching graphics. With obstacles
appearing every three seconds and getting more frequent and intense with time, the player will
need to make quick decisions during the continuous action.

Both players start with 3 lives. If a player’s car crashes into an obstacle, they lose a life. The
player who is able to survive the longest, wins.

Every element of the game, including player input processing, graphic output, and real-time
game logic, will be controlled by the FPGA. The logic and behavior of the game will be defined
in Verilog. The FPGA will be in charge of creating and updating obstacles, tracking the position
of the car, detecting collisions, producing visuals on a VGA display, and updating the lives.

Precise timing and synchronization are ensured via a 25 MHz clock signal, which guarantees
responsive gameplay and fluid graphics rendering. A number of modular components, each in
charge of particular duties, will be used to implement the game. In order to combine game
elements into a seamless visual experience, the input module will handle player controls, the
control module will handle game states, obstacle generation, and vehicle movement, and the
output module will handle visual display.

This project will provide a hands-on investigation of hardware-based interactive applications by
fusing the principles of digital design with game mechanics. The research will show how FPGAs
can handle real-time systems and provide a greater grasp of hardware-level programming by
using an FPGA. The game's modular design will make it simple to expand and modify, allowing
for the addition of features like extra lanes, multiplayer games, higher difficulty levels, and
exclusive bonuses.

To sum up, the goal of this project is to develop an engaging racing game for cars that blends
interactive gameplay, real-time graphics, and digital logic design. Through the use of an FPGA,
the project will offer a demanding and entertaining gaming experience in addition to practical
instruction in hardware design and real-time systems.
