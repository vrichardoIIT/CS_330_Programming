# Security Device Project 
by Vincent Richardo

## Abouts

Part 1

A computer science project for CS 330 course in IIT Fall 2022 written in JAVA, where we are tasked to make a simple security system that utilizes a finite state machine.
For the first part of the assignment, Users asked will input digits(access code) from 0 to 9, one at a time. if the inputs follows the sequence, 997061 the system will be unlocked and if the user input the following sequence 997064, it will lock the system.

Part 2

In the second part of a assignment, we try to bypass the access code but using a random number generator, we then estimate how long it would take on average to unlock the system and also find the mininum, maximum and average amount of tries to crack the code.


Codes has been tested on Eclipse IDE and windows 10 and 11 command prompt

## Prerequisites
before starting make sure that both git and JAVA is installed on your device. I recommend JAVA 16 or higher.

## Setup
### set up instructions are written based on a windows environment(command prompt) 
firstly clone the repository, enter the following statement to your command prompt at you desired location
    
    
    git clone https://github.com/vrichardoIIT/CS_330_Programming.git
  
executable is already created so there is no need to make one. However, if one choose to they my run the following statement
(gradle is required inorder to proceed).
   1, for part one:
   
   * navigate to the repository
              
              cd .\CS_330_Programming
        
        
   * delete old build
                
                gradle clean
        
   * build executable 
          
             gradle shadowJar
            
   2, for part two, we follow the same process as part one. however, because the project is located in a different location we must navigate to that location
      
   * navigate to PART2
      
          cd .\CS_330_Programming\PART2
          
   * repeat pervious step
      
      
## Follow the steps to run executable.
 - to run part one of the assignment run the following 
        
        java -jar CS_330_Programming/app/build/libs/app-all.jar
        
- to run part two of the assignment run the following
        
        java -jar CS_330_Programming/PART2/lib/build/libs/lib-all.jar
        
note: Repository location differ between individual 

## Guide
### Part 1
for part one, enter a numbers from 0-9 one that a time. be sure to press enter after each digits

### Part 2
Run the jar file and repeat as many time as you wish
      
          









