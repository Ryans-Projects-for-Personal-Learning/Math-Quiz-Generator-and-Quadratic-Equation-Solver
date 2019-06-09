# Elementary Math Quiz Generator / Quadratic Equation Solver

# About

This assignment was completed for ITI1120: Introduction to Computing I in Fall 2017, a first year course that introduces students to computer science concepts using Python. The purpose of this assignment was to explore loops, exception handling and the basics of designing a simple program. 

This program has 2 options: A math quiz generator for elementary school students and a quadratic equation solver for high school students.

This repository was created to archive the code for demonstration / educational purposes only. 

The program is completely functional except for a few instances where an invalid input would terminate the program (we were not expected to implement exception handling to all cases and were allowed to assume correct inputs from the user).

# Using the Program

To use the program, simply download the repository and open the file. You'll be prompted to follow instructions to access options and begin using the features right away. 

# Elementary Math Quiz Generator

The math quiz generator is for elementary school students who wish to practice their arithmetic skills, particularly in subtraction and exponents. The user will be asked to select what type of quiz they would like to do (subtraction or exponents) and then input how many questions they would like to practice. 

The quiz will begin and the user will answer the questions and receive feedback. If their answer is correct, the program will simply move onto the next question. If it is wrong, the program will print a message saying that the answer is incorrect and provide the correct answer. 

At the end of the quiz, a score will be calculated and display the result. 

# Quadratic Equation Solver 

The solver solves quadratic equations by taking as inputs, the values of 3 variables, a, b and c and will use these values to compute the real roots using the quadratic formula. 

One warning to keep in mind is that the value of a cannot be 0 as this results in a division by 0 error. The program will take this into account, inform the user of this warning and restart the program, prompting the user to enter valid inputs. 
