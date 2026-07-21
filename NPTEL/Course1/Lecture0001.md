# Chapt 1: Introduction to Computer Architecture (Smruti Sarangi)


## What is Computer Architecture?

Answer : It is the study of computers?

* **Computer Architecture**
  * The view of a computer as presented to software designers
* **Computer Organization**
  * The actual implementation of a computer in hardware

What is a computer?

A computer is a general purpose device that can be programmed to process information, and yield meaningful results.

## How does it work?

![alt text](image.png)

## What does a computer look like?

![alt text](image-1.png)

* In this course we will be primarily see - CPU, Memory and harddisk

![alt text](image-2.png)

* Let us make it a full system ...

![alt text](image-3.png)

* Food for Thought - What is most intelligent computer?

Answer - Our brilliant brains

![alt text](image-4.png)

* How to Instruct a Computer

![alt text](image-5.png)

## What Can a Computer Understand?

![alt text](image-6.png)

## The Language of Instructions


![alt text](image-7.png)

What is ISA - It is set of Instructions

## Features of an ISA

* Example of instructions in an ISA
  * Arithmetic instructions : add, sub, mul, div
  * Logical instructions : and, or , not
  * Data transfer/movement instructions
* Complete
  * It should be able to implement all the programs that users may write

## Features of an ISA - 2

![alt text](image-8.png)

## Designing an ISA

![alt text](image-9.png)

## RISC VS CISC

A reduced instruction set computer (**RISC**) implements
simple instructions that have a simple and regular
structure. The number of instructions is typically a small
number (64 to 128). **Examples: ARM, IBM PowerPC,
HP PA-RISC**  

A complex instruction set computer (**CISC**) implements
complex instructions that are highly irregular, take multiple
operands, and implement complex functionalities.
Secondly, the number of instructions is large (typically
500+). **Examples: Intel x86, VAX**

## Summary Uptil Now ...

* **Computers** are dumb yet ultra-fast machines.
* **Instructions** are basic rudimentary commands used to
communicate with the processor. A computer can execute
billions of instructions per second.

* The **compiler** transforms a user program written in a high level language such as C to a program consisting of basic machine instructions.
* The **instruction set architecture(ISA**) refers to the semantics of all the instructions supported by a processor.
* The instruction set needs to be **complete**. It is desirable if it is also **concise**, **generic**, and **simple**.