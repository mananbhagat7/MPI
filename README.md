# MPI
This repository is to learn MPI called Message Passing Interface. Here, I will pull and push all data related to MPI. 
1] Home work 1: Introduction to MPI 

Homework given was:

   1] Write the “Hello World” program from above so that every process prints out its rank and the size of the communicator (for example, process 3 on a communicator of size 5 prints “Hello World from process 3 out of 5!”).
   2] Write a program in which the the processes with even rank print “Hello” and process with odd rank print “Goodbye.” Print the process number along with the “Hello” or “Goodbye” (for example, “Goodbye from process 3”).
   3] Sometimes the program you write can only run correctly if it has a certain number of processes. Although you typically want to avoid writing these kinds of programs, sometimes it is inconvenient or unavoidable. Write a program that runs only if it has 5 processes. Upon failure, the root node should print “Error: This program must run with 5 processes” and upon success it should print “Success!” To exit, call the function Comm.Abort().
