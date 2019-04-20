# trains.c
An exercise for C where you create metro management software


## Project Aim
To Enable you to:
* Think outside the box and implement your knowledge of programming concepts and coding into
design and implementation of a real-life scenario.
* Become more pro in defining and using variables, functions, loops and conditional statements in
a software program.
* To be able to understand requirements and customize your design based on a new idea and
turn it into a functional software program.

## Requirements and Expectations from the System
* Come up with a scheduling system based on trains operating 12 hours in every 24 hour. For
example: Trains travelling every 2 hours will create 6 time frames (time blocks).  
* Ask the end user (system controller) how many trains are going to be operating that day?  
* Ask the system controller what time frame are the trains going to be travelling in?  
* Check if there is more than one train in one block?  
* If there is more than one train crossing the tracks in the same time block, only set the signal
status for one of them at the time to “green” and alert ALL other trains with “stop” or “red”
signal.  
* Once the train moved from track in that time block, reset the “red” signal to “green” for all
other trains.  
* Repeat Steps as necessary.