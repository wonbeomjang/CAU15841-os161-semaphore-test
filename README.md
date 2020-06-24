# CAU15841-os161-semaphore-test

This repository for OS assingment.

## Problem
Traffic through major intersections in Heukseok-dong has increased over the past few years. 
Now, the huge stalemate has led to the admission that those who go to and from Chung-Ang University need a more efficient way to get traffic through the intersection. 
Your mission is to design and implement solutions using semaphores.
Create a report that explains how to resolve the deadlock and submit it.

<img src="https://user-images.githubusercontent.com/40621030/85597426-93839080-b685-11ea-980a-c9ee6fde79d2.png" alt="drawing" width="200"/>

## Requirements
- There can't be two cars at the same part of the intersection at the same time. (This is called an accident.)
- You need to improve the flow of traffic while preventing traffic from waiting infinitely waiting. (Difficult Task)
- Each vehicle must be printed when approaching, entering and leaving the intersection with outputs indicating the vehicle number, approach direction and destination direction. You must invoke the message function provided for printing.



code is in [https://github.com/wonbeomjang/os161/blob/master/kern/test/synchtest.c](https://github.com/wonbeomjang/os161/blob/master/kern/test/synchtest.c)
