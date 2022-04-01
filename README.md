# Project 2: CPU Scheduling Simulation 
- Author: Anthony Diep
- Class: CS321 Section 2
- Semester: 2

## Overview
This program implements two hash tables using linear and double probing.

## Reflection
After finishing the lab, I felt more conceptually knowledgable of how a hash table works. I thought the procedures of the lab were pretty straightforward, the implementation of HashObject.java, LinearProbing.java and DoubleHashing.java I felt were straightforward. Of course, most of my troubles came from HashTable.java and HashTest.java where I kept experiencing many troubles mainly from outputting the correct values of average probes. For some reason, my table just inserted more values than what was expected with two different methods I used (StringTokenizer and BufferedReader) and I just never understood why. 

Overall, implementing the program was straightforward but I of course overlooked through some things. I do however think that the majority of the logic implemented in the hash table is correct. Alongside that, I believe that I implemented the LinearProbing and DoubleHashing correctly after going through many trials. I've went through a good amount of time to figure out why my average probes were lower than expected where I've exhausted all of my thoughts of solutions to it. If the error is indeed small as I expect it, hopefully recognition towards the implemented logic can be given as that small error can cause massive differences among expected and actual results of similar programs.

## Compiling and Using
To compile the code, run `$javac *.java`.


To run the code, run `$java HashTable <input type> <load factor> [<debug level>]`
1. input type: The type of data to be inserted
2. load factor: The desired load factor that the tables should maintain
3. debug level (optional): `0` for summary of experiment on console, `1` for summary of experiment on console and to print number of duplicates and number of probes into linear-dump and double-dump
    
## Program design and important concepts:
HashTest.java is the main driver of the program where depending on the command line arguments, will create two tables, one that uses linear probing and the other double, fitted with the desired data type and load factor. LinearProbing.java and DoubleHashing.java contain the algorithm needed to do the hashing for a hash table's "put" method. HashObject.java is the object containing the desired input type along with other information that is hashed into the tables created.
  
## Sources used
1. [The Oracle Documentation]( https://docs.oracle.com/javase/7/docs/api/java/util/Random.html) for a

  
  
