# Report

 ## Introduction
-   A Calculator is a device which performs arithmetic calculations on numbers. The simplest calculator can only perform Addition, Substraction, Multiply, Division but this calculator can perform Square & Percentage as well. In our day to day life we have to perform various calculations which when done manually takes a lot of time so this assignment was centered on the Design & Implementation of a simple calculator to perform simple arithmetic calculations. The manual system is investigated in detail with a view to finding out the need to automate the system. Intrestingly, The end result of the simple calculator system made using a simple code in C has its ability to process the numbers with the operators and perform the arithmetic calculations. 

## 4W and 1H
### WHY 
-   To solve the arithmetic calculations with ease.
-   Very easy to use.
-   User friendly.

### WHERE
-   Used in different shops and industries.
-   Used in our homes to perform simple calculations.
### WHO
-   Anyone can use it.
-   No complex functions or features.
### WHEN
-   It can reduce the time duration of manual calculations.
-   It is used in busy schedule of the employees which saves a lot of time.
-   It can be accessed any time and anywhere and by anyone.
### HOW
-   By simply clicking the keys i.e. numbers abd operators.
## SWOT analysis
### STRENGTHS
-   Able to solve complex arithmetic calculations with ease.
-   User friendly and very easy to use.
### WEAKNESS
-   Performs only one calculation at a time.
### OPPORTUNITIES
-   Able to perform multiple functions at single time.
-   Solve more complex functions.
### THREATS
-   Many Complex calculator are there in the market.
-   Solves only simple arithmetic problems.
## Requirements
### High level requirements
|ID|Description|	
|:--:|:--:|
|HLR1|Addition|
|HLR2|Multiplication|
|HLR3|Subtraction|
|HLR4|Division|
|HLR5|Square|
|HLR6|Percentage|
### Low Level requirements
#### LLR1
|ID|HLR ID|Description|
|:--:|:--:|:--:|
|LLR1|HLR1|Declare the local variables|
|LLR1.1|HLR1|Print the Choice (Addition)|
|LLR1.2|HLR1|Enter your Choice|
|LLR1.3|HLR1|Take the numbers|
#### LLR2
|ID|HLR ID|Description|
|:--:|:--:|:--:|
|LLR2|HLR2|Declare the local variables|
|LLR2.1|HLR2|Print the Choice (Multiplication)|
|LLR2.2|HLR2|Enter your Choice|
|LLR2.3|HLR2|Take the numbers|
#### LLR3 
|ID|HLR ID|Description|
|:--:|:--:|:--:|
|LLR3|HLR3|Declare the local variables n1, n2, res|
|LLR3.1|HLR3|Print the Choice (Subtraction)|
|LLR3.2|HLR3|Enter your Choice|
|LLR3.3|HLR3|Take the numbers|
#### LLR4
|ID|HLR ID|Description|
|:--:|:--:|:--:|
|LLR4|HLR4|Declare the local variables n1, n2, res|
|LLR4.1|HLR4|Print the Choice (Division)|
|LLR4.2|HLR4|Enter your Choice|
|LLR4.3|HLR4|Take the numbers|
#### LLR5 
|ID|HLR ID|Description|
|:--:|:--:|:--:|
|LLR5|HLR5|Declare local variables n1, n2, res|
|LLR5.1|HLR5|Print the Choice (Square)|
|LLR5.2|HLR5|Enter your Choice|
|LLR5.3|HLR5|Take the numbers|
#### LLR6
|ID|HLR ID|Description|
|:--:|:--:|:--:|
|LLR6|HLR6|Declare local variables n1, n2, res|
|LLR6.1|HLR6|Print the Choice (Percentage)|
|LLR6.2|HLR6|Enter the Choice|
|LLR6.3|HLR6|Take the numbers| 

# Test Plan
    
    * Testing of addition
                  * Addition of no's

    * Testing of multiplication
                   * Multiplication of no's

    * Testing of subtraction
                   * Subtraction of no's

    * Testing of division
                   * Division of no's
                   * Division by 0

    * Testing of square
                    *  Square of a no



     _______________________________________________________________________
    | TEST CASES |  VALUES      | EXPECTED RESULT | ACTUAL RESULT | SUCCESS |
    | ADDITION() | A=1 B=3      | OUTPUT= 4       | OUTPUT=4      | YES     |
    | ADDITION() | A=4 B=-5     | OUTOUT= -1      | OUTPUT= -1    | YES     |
    | ADDITION() | A=2 B=2 C=2  | OUTPUT= 6       | OUTPUT= 6     | YES     |
    | MULTIPLY() | A=2 B=4      | OUTPUT= 8       | OUTPUT= 8     | YES     |
    | MULTIPLY() | A=2 B=0      | OUTPUT= 0       | OUTPUT= 0     | YES     |
    | MULTIPLY() | A=2 B=-3     | OUTPUT= -6      | OUTPUT= -6    | YES     |
    | MULTIPLY() | A=-2 B=-2    | OUTPUT= 0       | OUTPUT= 0     | YES     |
    | SUBTRACT() | A=2 B=1      | OUTPUT= 1       | OUTPUT= 1     | YES     |
    | SUBTRACT() | A=2 B=-5     | OUTPUT= -3      | OUTPUT= -3    | YES     |
    | SUBTRACT() | A=-2 B=-5    | OUTPUT= -7      | OUTPUT= -7    | YES     |
    | DIVISION() | A=6 B=2      | OUTPUT= 3       | OUTPUT= 3     | YES     |
    | DIVISION() | A=5 B=2      | OUTPUT= 2.5     | OUTPUT= 2     | NO      |
    | DIVISION() | A=6 B=0      | OUTPUT= ERROR   | OUTPUT= ERROR | YES     |
    | SQUARE()   | A=6          | OUTPUT= 36      | OUTPUT= 36    | YES     |
    | SQUARE()   | A=-6         | OUTPUT= 36      | OUTPUT= 36    | YES     |
