**README**

This repository is the collection of Assignments completed for Parallel Computing Course (CS633A) at IIT Kanpur. All assignments are implemented using MPI (Message Passing Interface) communication protocol for Parallel Computing.

All the parallel programs are executed on the IIT Kanpur CSE-Computer lab cluster that contains 60 computers using MPICH implementation of MPI.

Details about the Assignments:

**Assignment1:**  

In this assignment, implemented a parallel program to compare the performance of point to point communication methods MPI_Send, MPI_Recv under three scenarios:
  * When MPI_Send \& MPI_Recv are used to transmit each data item between communicating processes
  * WHen MPI_Send/MPI_Recv are used with MPI_Pack/MPI_Unpack to transmit multiple data items togather between communicating processes.
  * When multiple data elements are grouped togather using MPI derived data types and transmitted using MPI_Send/MPI_Recv between communicating processes.  
 
 The performance is measured in terms of execution time of parallel processes. More details can be found in the Assignment 1 directory.
 
 **Assignment2:**  
 
 In this assignment, implemented network topology aware optimisations to the following four MPI Collective communication calls to optimise the MPI Collective communications
  * MPI_Bcast
  * MPI_Reduce
  * MPI_Gather
  * MPI_Alltoallv  

The performance of the optimisations are studied by scaling up the number of parallel processes and amount of data communicated. More details can be found in the Assignment 2 directory.

**Assignment3:**

In this assignment, implemented a parallel program to process a large Temperature data set to derive insights from the data bydistributing chunks of data across different parallel processes.

MPI communication protocol was used for inter process communication. Studied the scaling of code by varyingnumber of compute nodes and processes per node.

More details can be found in the Assignment 3 directory.
