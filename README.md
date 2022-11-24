# Security Device Project 
by Vincent Richardo

## Abouts
A computer science project for CS 330 course in IIT Fall 2022 written in JAVA, where we are tasked to make a simple security system that utilizes a finite state machine.
For the first part of the assignment, Users asked will input digits(access code) from 0 to 9, one at a time. if the inputs follows the sequence, 997061 the system will be unlocked and if the user input the following sequence 997064, it will lock the system.

In the second part of a assignment, we try to bypass the access code but using a random number generator, we then estimate how long it would take on average to unlock the system and also find the mininum, maximum and average amount of tries to crack the code.

### State Transition Diagram
![image](https://user-images.githubusercontent.com/118873376/203544246-01190b49-8b2f-495e-93eb-8343ff80c1a7.png)

Codes has been tested on Eclipse IDE


## Setup
firstly clone the repository
$ git clone https://github.com/vrichardoIIT/CS_330_Programming.git

next Build executable
$ ./gradlew jar


