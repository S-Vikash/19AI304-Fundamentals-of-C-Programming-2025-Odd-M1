# 19AI304-Fundamentals-of-C-Programming-2025-Odd-M1
# IAPR-1- Module 1 - FoC
## 1. Implementation of basic C programs using Literals,Consonants, Variables, Data types.
## 2. Implementation of different categories of operators.
# Ex.No:1
  Build a C program to demonstrate the usage of different types of literals: integer, float, character, and string.  

# Aim:
To build a C program that prints integer, float,character, and string literals on the console using the printf() function.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Inside the main() function, use printf() to display each literal along with its size in bytes using sizeof() :
  
   3.1 Integer literal (e.g., 10) using `%d`
   
   3.2 Float literal (e.g., 3.14) using `%f`
   
   3.3 Character literal (e.g., 'A') using `%c`
   
   3.4 String literal (e.g., "Hello C") using `%s`
   
### Step 4: 
   Stop
# Program:

#include <stdio.h>

int main() {

    int intLiteral = 100;
    
    float floatLiteral = 12.345;

    char charLiteral = 'A';
    
    char stringLiteral[] = "Hello, Susmitha!";
    
    printf("Integer Literal: %d\n", intLiteral);
    
    printf("Float Literal: %.3f\n", floatLiteral);
    
    printf("Character Literal: %c\n", charLiteral);
    
    printf("String Literal: %s\n", stringLiteral);
    
    return 0;
    
}

# Output:

<img width="1681" height="400" alt="Screenshot 2025-11-19 132031" src="https://github.com/user-attachments/assets/7131cd50-107c-4010-81dd-d73072d0e05e" />


# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.
