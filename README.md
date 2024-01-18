# FPGA-GAME-SV

https://github.com/YASHASVASISHTA/FPGA-GAME-SV/assets/112754882/0669b49a-7320-4c2e-b31e-50c508659ca2


Project Report: FPGA-based Tic-Tac-Toe Game Implementation

1. Introduction

The purpose of this project was to design and implement a Tic-Tac-Toe game on a Field-Programmable Gate Array (FPGA) platform. The project involved utilizing hardware description languages (HDL) to define the game logic, implement it on the FPGA, and interface it with user input/output devices.

2. Objective

The main objective of the project was to create a functional and interactive Tic-Tac-Toe game that leverages the parallel processing capabilities of an FPGA. This involved designing the game logic, developing the necessary hardware components, and interfacing with input devices (e.g., switches and buttons) and output devices (e.g., LEDs and displays).

3. Hardware and Software Tools

The project utilized the following hardware and software tools:

FPGA Board: BASYS 3 ARTIX -7
Development Environment:  Xilinx Vivado
HDL: System Verilog for describing hardware components
Simulation: ModelSim

4. Design Overview

The Tic-Tac-Toe game was divided into several modules:

Game Logic: This module implemented the core game logic, including the board state, player turns, win/lose conditions, and tie detection.
User Interface: The user interface module handled user input from switches or buttons, displaying the game state on LEDs or a display.
Reset and Control: Implemented a control module to manage game resets and other control signals.
5. Implementation Steps

The project followed these general implementation steps:

Game Logic Implementation: Defined the rules and conditions for the Tic-Tac-Toe game in HDL.
User Interface Design: Developed modules for interfacing with user input devices and displaying game information.
Integration: Integrated the game logic and user interface modules into a complete system.
Simulation: Conducted simulations to verify the correctness of the design and debug any issues.
FPGA Implementation: Synthesized the design for the target FPGA platform and programmed the FPGA.
Testing: Tested the functionality on the physical FPGA board, ensuring proper interaction with user input/output devices.
6. Challenges and Solutions

Throughout the project, several challenges were encountered, such as timing issues, debouncing switches, and optimizing resource utilization. Solutions were devised through iterative design, simulation, and consultation of FPGA documentation and forums.

7. Results and Performance

The implemented Tic-Tac-Toe game demonstrated reliable and responsive performance on the FPGA platform. It successfully leveraged the parallel processing capabilities of the FPGA, providing an interactive gaming experience.

8. Conclusion

The project successfully achieved its objectives by implementing a functional Tic-Tac-Toe game on an FPGA. The utilization of hardware description languages and the parallel processing capabilities of the FPGA contributed to the efficiency and responsiveness of the game.

9. Future Work

Possible areas for future improvement include implementing more sophisticated game features, optimizing resource utilization, and exploring additional input/output options.

10. Acknowledgments

I would like to express gratitude to PAVITRA Y J  for guidance and support throughout the project.
