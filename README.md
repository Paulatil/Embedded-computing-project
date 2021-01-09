# This file gives insight into the different sub-projects under the Embedded computing project module

The embedded project class comprises two sub-projects namely:

1. coffee maker software project

2. random math problem ineractive game

1. THE COFFEE MAKER PROGRAM:

This project was implemented adopting both bare-metal programming approach and multithreading approach. 

The bare-metal programming approach was written both in AM assebly language and C. The multithreading model was implemented in C using CMSIS_RTOS2 API. Programs were sufficiently tested and dubegged on an embedded platform. 

SYNOPSYS:
 The coffee maker project was designed to solve the problem of coffee brewing through automation process that uses microcontrollers inplace of conventional mechanical brewing systems. The objective was ti be able to build a more reliable, cheaper, an reliable coffee make machine using the state-of-the-art technology.
 With sensors (temperature and pressure) simulated by code, the coffee maker software is able to bring up the temperature to a desired value set by the user. Also, the brew stage timer and pressure can alse be set by user at initial point of initilaizing or re-setting he machine. The software is able to monitor the temperature and pressur in real-time, with ability to display both readings, time the brew process, and indicate to user when both brew atrts and stops. 
 
 
 2. RANDOM MATH PROBLEM INTERACTIVE GAME:
 
 This project was implemented adopting the multithreading programming model to enable multiple processes run simultaneously. CMSIS_RTOS2 API was the real-time operating system API implemented for the project. Software was sifficiently tested and debugged on an embedded platform. 
 
 SYNOPSYS:
 The embedded software is an interactive educational game with the capability of randomly generating math problems and math operators. The difficulty of the math problems is set by the player, which deteremins the dgigit size for each number generated. A player interacts with the game via a hyperterminal interface, and feedback on player's responses is given through audio tones. The game also randomly generates certain gesture questions for the player to carry out.  
