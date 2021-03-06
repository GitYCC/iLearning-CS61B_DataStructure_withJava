# CS 61B  Homework 1  

*Excerpts from: https://people.eecs.berkeley.edu/~jrs/61b/hw/hw1/*

This homework assignment is meant to make sure you can write, compile, and run
simple Java programs.  
  
## Problem 1
Write a program that reads a String from the keyboard.  The program should then
construct a URL for http://www.X.com/, replacing X with the String read in, and
print the first five lines of the Web page at that URL in REVERSE ORDER; i.e.,
the fifth, fourth, third, second, and first lines.  

We've already created a skeleton for you in the file OpenCommercial.java; you
just need to fill it in.  Use the println method to print each of the five
lines, so that there's a carriage return at the end of each line.  

To receive credit for this problem, you must follow these directions exactly:

1. Your solution must be in a file called OpenCommercial.java .
2. Do not edit any of the lines before the line that says 
           "Replace this comment with your solution."
3. Your program must print only five lines from the given home page,
           and must print them in reverse order.  Do not add any extraneous
           println statements.  Do not modify the lines before printing them.
           The program skeleton we've given you prints a prompt before reading
           the String; don't change this prompt.  Your program must produce
           EXACTLY the same output as our solution, because we will be using an
           automatic grading program dumber than a microwave oven.

Before you submit your solution, be sure to try compiling your program ON THE
LAB MACHINES with "javac -g OpenCommercial.java", and be sure to try running
your program ON THE LAB MACHINES using "java OpenCommercial".  If you are
working from home, be aware that there might be slight differences between your
Java installation and ours, so you should always test your code on the lab
machines just before you submit it.  No partial credit will be given for
programs that don't produce a portion of a Web page.
  
## Problem 2
Write a program called "Nuke2.java" containing a class called Nuke2 whose main
method reads a string from the keyboard and prints the same string, with its
second character removed.  (That's character number 1, since Java numbers
characters in a string starting from zero.)  In other words, after you run
"java Nuke2", if you type in the string "skin", the program will print "sin".

(Note:  your program might crash with an error message if you type in a string
containing fewer than two characters.  That's okay; your program only needs to
work correctly on strings at least two characters long.)

To receive credit for this problem, you must follow these directions exactly:

1. Your solution must be in a file called Nuke2.java, and the main
           program must be in a class called Nuke2.
2. Your program must read just one string, then print the same string
           with the second character omitted, then exit.  Do not print anything
           else.  In particular, DO NOT PRINT A PROMPT.

Again, be certain that your program compiles and runs correctly on the lab
machines before you submit it!  The automatic grader is not charitable.
Did I mention that you should NOT PRINT A PROMPT?
