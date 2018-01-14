# IDEA: Improve on an existing programming assignment or make a new equivalent one


## CS8
 
| Assignment Choices |
|--------------------|
| Team of one or two: Create an testing assignment (see details below) |
| Team of one or two: TBD (See Richert) |


## CS16
 
| Assignment Choices |
|--------------------|
| Team of two: Convert [F17 CS8 lab07 scrabble](https://ucsb-cs8-f17.github.io/lab/lab07/) into a CS16 assignment  |
| Team of two: Create an testing assignment (see details below) |
| Team of two: Make an assignment about debugging.  Not necessarily gdb, but more like debugging strategies.   The outcome should be that students understand debugging strategies.   (e.g. print statements in the right place, etc.) |  
 
## CS24
 
| Assignment Choices |
|--------------------|
| Team of two: Create an testing assignment (see details below) |
| Team of two: Improve the labs. |
| Solo: (Jack) |

## CS56
 
| Assignment Choices |
|--------------------|
| Team of two: Create an testing assignment (see details below) |
| Team of two: TBD See Phill |

 
# Testing Assignment

This assignment can be done in the context of each of the four courses (8,16,24,56).

The assignment will have some prompt for writing code, and then there will be a collection of implementations, say 6 of which are buggy, and 6 of which are correct.    The student's job is to WRITE A SUITE OF TEST CASES that always reports at least one failure for each buggy implementation, and where all the test cases pass for the correct implementations.  The students will NOT be given the source code for all 12 implementations.  They might be given, say, 2 correct ones and two buggy ones.  But the others will be "closed source"---they will only know, from submit.cs output, which of these happened:  
   * Implementation was buggy, and student test case reported buggy (OK)
   * Implemntation was correct, and student test case reported buggy (NOT OK)
   * Implementation was buggy, and student test case reported correct (NOT OK )
   * Implemntation was correct, and student test case reported correct (OK)
   
