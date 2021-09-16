## Overview of programming
- "Program" is the sequence of instruction to perform some task in the computer
- "Programming" is the process of writing program 

## Stages of executing program
- High level language is transformed to Assembly level language
- Assembly level language is transformed to Machine level language
- Assembly level language is known to be low level language 
- High Level language is a "Source code"
- Assembly language is a "Object code"
- Machine level language is "Machine code"
- Machine code is fundamental to computer processor
- Machine code is the sequence of 0's and 1's
- Assembly code is a symbolic representation of source code
- High level language is easier to learn 
- High level language will be in understanding language like ENGLISH
- High level language is machine independent
- Assembly and machine language is machine dependent
- Machine language can only be understand by machines
- Languages like c,c++, COBAL uses "Compiler" for transforming high level language to low level language 
- Languages like Python,BASIC uses "Interpreter" for transforming high level language to low level language
- Java language uses both compiler and interpreter for transforming high level language to low level language
- Difference between compiler and interpreter is that compiler transforms entire  program from High level language to low level language whereas interpreter transforms line by line program from high level language to low level language
- Assembler is used for transforming assembly code to Machine code 

## Applications for programming
- Install GCC compliler for transforming High level language to low level language
- Install Visual studio code
- Install GIT

## Steps for programming
- Create a new file in visual studio code for each programming
- Consider file name as test1.c
 #include <stdio.h>

int main()
{
    printf("This is my first program");
    return 0,
}

- Open terminal (ctrl+j) and use the below syntax, an assembly file will be generated (in this a.exe is default)
- syntax: gcc filename
- command: gcc test1.c

# Changing assembly file name
To change the output file name, use the below syntax
- syntax: gcc filename -o outputfilename
- command: gcc test1.c -o test1

# Execute Assembly File
To execute the output file, use the below syntax
- syntax: ./outputfilename
- command: ./a.exe or ./test1.exe

