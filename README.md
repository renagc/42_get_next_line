# Get Next Line

Reading a line from a file descriptor is often a tedious task. The Get Next Line project aims to solve this problem by providing a function that returns a line read from a file descriptor. This project not only introduces a convenient function but also teaches the concept of static variables in C programming.

## Goals

The main goal of this project is to implement the get_next_line() function, which reads a line from a file descriptor. The function should be able to read the text file one line at a time through repeated calls. It should return the line that was read, including the terminating newline character. If there is nothing else to read or if an error occurs, the function should return NULL.

## Common Instructions

The project must be written in C and follow the Norm guidelines.
Functions should not exit unexpectedly, except for undefined behaviors.
Proper memory management is required, and no leaks are allowed.
A Makefile should be included, with necessary rules for compilation and cleaning.
Bonuses should be implemented in a separate file if applicable.
Tests are encouraged to ensure functionality and facilitate the defense.

## Mandatory Part

The mandatory part of the project focuses on implementing the get_next_line() function. The function should be able to read lines from a file descriptor and return them. The requirements include handling various scenarios, such as reading from a file or reading from standard input. The function should handle newline characters appropriately and include the necessary helper functions.

## Bonus Part

The bonus part of the project provides an opportunity for additional challenges. In this case, the challenge is to implement get_next_line() using only one static variable. Additionally, the function should be able to manage multiple file descriptors simultaneously, allowing reading from different descriptors without losing the reading thread of each one.
