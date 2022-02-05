# Project 1: Warm-up with Application of Linked List to Simulate Cache
- Author: Anthony Diep
- Class: CS321 Section 2
- Semester: 2

## Overview
This program implements and tests a cache data structure which was made using a LinkedList data structure.

## Reflection
Personally, I think this was an extremely good first project for the class. For me, CS321 is my first CS class in BSU (I challeneged 123 and I has credits to transfer for 223). I was worried that I was going to struggle in this class as I consider C++ to be my "first" language. I really linked this lab because it didn't necessarily introduce anything new but it challenged your basic java knowledge with the input/outputs and the use of the DLL data strucutre.

I think my main challenge was reading the file. Normally, I would use a regular Scanner object and use a while loop like:
```
while(scanner.hasNext()){
    String word = scanner.next();
}
```
which gave a lot of errors. I then found out about the StringTokenizer class when I went for tutoring which made things so much easier to work with. I genuinely enjoyed this lab because it served as a good basis and confidence booster for what's to come.

## Compiling and Using
To compile the code, run `$javac *.java`. Test.java has two valid obtions for the user to run; whether 1 or 2 caches are to be used. Test.java also requires a textfile to parse through. 

If the desire is to use *one* cache, run the following: `java Test 1 <size of cache> <text file>`. 
If the desire is to use *two* caches, run the following: `java Test 2 <size of cache 1> <size of cache 2> <text file>`.
  
## Sources used
1. [The Oracle Documentation](https://docs.oracle.com/javase/7/docs/api/java/util/LinkedList.html) for a Linked List was used to get more information on different methods that the LinkedList class have.
2. [Article on Caches by GeeksforGeeks](https://www.geeksforgeeks.org/cache-memory-in-computer-organization/#:~:text=Cache%20Memory%20is%20a%20special%20very%20high%2Dspeed%20memory.&text=The%20cache%20is%20a%20smaller,which%20store%20instructions%20and%20data.) was used for more information on how a cache worked.
3. I was taught by Jonathan Porter from the Kount Tutoring Center and aided by this [Youtube video](https://www.youtube.com/watch?v=jMbbvMeZuDc&t=0s) on more information on how a StringTokenizer worked.
  
  
