---
title: 'Part 1 - Start Programming'
nav_order: 2
hidden: false
---

Computer programs consist of _commands_, that is, simple instructions that the machine executes one at a time. Commands can, for example, perform calculations, compare data in the machine's memory, cause a change in the operation of the program, or convey messages and query the user for information.

Let's start learning about programming with a simple command `print`, which _prints_ text. Printing basically means that the program displays text on the screen.

For example, the following program prints the line "Hello everyone!":

`` `python
print ("Hello everyone!")
`` `

When we run the program, it produces the following result:

Hey everyone!

Note that the program code must be written exactly as above for it to work. For example, if we try to print a line without using quotation marks

`` `python
print (Hi everyone!)
`` `

the program does not work and results in the following error message:

So Python can't interpret printable text correctly if it's not in quotation marks.

## Program progress

When you write several commands in a row,
they are performed in order from top to bottom.
For example, a program

`` `python
print ("Welcome to learning programming!")
print ("Practice using the print command first.")
print ("This program prints three lines of text on the screen.")
`` `
print the following lines on the screen:

Welcome to learn programming!
First, practice using the print command.
This program prints three lines of text on the screen.
