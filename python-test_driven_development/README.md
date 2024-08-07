
Here's a summarized README.md file for your Python Test-Driven Development (TDD) project:

Python Test-Driven Development (TDD)
Project Overview
This project focuses on Test-Driven Development (TDD) in Python. The goal is to write tests and documentation first before implementing any functionality. You will be working on various Python functions, ensuring that they meet specified requirements and handle edge cases effectively.

Learning Objectives
By the end of this project, you will understand:

The importance of TDD and writing tests before code.
How to write docstrings for modules and functions.
How to create and run tests using Python's doctest and unittest modules.
How to identify and test edge cases.
Project Requirements
Python 3.8.5 on Ubuntu 20.04 LTS.
All scripts must have a shebang (#!/usr/bin/python3) at the top.
Follow pycodestyle for code formatting.
All test files should be placed in a tests/ directory.
Tests should be executable using python3 -m doctest ./tests/* and python3 -m unittest.
Project Structure
Files and Directories
0-add_integer.py: Function that adds two integers.
2-matrix_divided.py: Function that divides all elements of a matrix.
3-say_my_name.py: Function that prints "My name is <first name> <last name>".
4-print_square.py: Function that prints a square using #.
5-text_indentation.py: Function that prints a text with 2 new lines after ., ?, and :.
tests/: Directory containing test files for each function.
Tasks
Integers addition (0-add_integer.py)

Function that adds two integers.
Raises TypeError if inputs are not integers or floats.
Divide a matrix (2-matrix_divided.py)

Function that divides all elements of a matrix by a given number.
Handles division errors and matrix validation.
Say my name (3-say_my_name.py)

Function that prints a name in the format "My name is <first name> <last name>".
Ensures inputs are strings.
Print square (4-print_square.py)

Function that prints a square of a given size using #.
Validates that size is a positive integer.
Text indentation (5-text_indentation.py)

Function that prints text with 2 new lines after ., ?, and :.
Max integer - Unittest (tests/6-max_integer_test.py)

Write unittests for the function max_integer.
