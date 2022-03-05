# Project 2: CPU Scheduling Simulation 
- Author: Anthony Diep
- Class: CS321 Section 2
- Semester: 2

## Overview
This program implements a max heap data structure to simulate CPU Scheduling.

## Reflection
After completing this lab, I definately felt that there were more confusing parts to this lab compared to the first one. I think the thing I struggled most with was knowing which attribute of a Process was supposed to do in relation to the starter code given by the BSU Public Github account. For one, it took me quite a long time to understand what the timeRemaining attribute was and how it was different from maxProcessTime. Perhaps I just didn't understand the instructions enough for it. Also, I also found that there were a lot of confusing naming conventions used in the starter code. Things such as resetWaitingTime were confusing because why would it be "waitingTime" instead of "time remaining" or something more, in my opinion, related?

Overall, I felt that this was an ok project to do. I felt that a large part of this lab was just a "copy and paste" the codes taught in class to this project. If anything, I would be in more favorable to this project if the starter code was improved on.

## Compiling and Using
To compile the code, run `$javac *.java`.


To run the code, run `$java CPUScheduling <maxProcessTime> <maxPriorityLevel> <timeToIncrementPriority> <simulationTime> <processArrivalRate>`.
Where:
1. maxProcessTime: Maximum time for a given process to be required to finish
2. maxPriorityLevel: Maximum possible priority given to a Process
3. timeToIncrementPriority: The threshold to increment a Process's priority if it hasn't been processed within this time
4. simulationTime: Time for simulation
5. processArrivalRate: A probability for when a Process arrives into the queue
    
## Program design and important concepts:
**Many of the files used were borrowed from BSU public resources github**. All files that were borrowed will have a Javadoc comment at the top labeling it.

This program is not 100% correct, there does seem to be inaccuracies concerning the expected results but all test files given from BSU's github huns successfully without exiting abnormally. This program contains several interfaces for classes and one exception class for the heap. The "main" file in this program is "CPUScheduling.java" where the simulation starts. Files such as ProcesGenerator.java creates processes from the Process.java file and inserts them into a priority queue made up of MaxHeap.java and MyPriorityQueue.java.

  
## Sources used
1. [The Oracle Documentation]( https://docs.oracle.com/javase/7/docs/api/java/util/Random.html) for a reminder of how random number generation worked
2. [Article on Caches by GeeksforGeeks](https://www.geeksforgeeks.org/max-heap-in-java/#:~:text=A%20max%2Dheap%20is%20a,child%20at%20index%202k%2B2) was used for more information on how the CPU Scheduling worked
3. Starting code was taken from [BSU's github public resources](https://github.com/BoiseState/CS321-resources/tree/master/projects/p2)

  
  
