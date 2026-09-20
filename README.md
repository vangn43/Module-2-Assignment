# Pythonic Text Analyzer

## Project Overview
This project is a reworked version of a Python text analyzer. I changed the original code in order to make it cleaner and easier to understand. This program will read a text file and show the total number of words, unique words, the five most common words, and how many words have more than three characters.

## How to Run the Program
Open the project folder in VS Code and open the terminal, and then run:

python text_analyzer.py

The program will read the sample.txt file and show the results inside the terminal.

## Improvements made

### Pep 8
I changed the code to follow PEP 8 by using snake_case, proper spacing, and cleaner function names.

### Context Manager
I used a with statement to open the file so it automatically closes after Python is done reading it.

### List Comprehension
I used a list comprehension to find all of the words that have more than three characters.

### Collections counter
I used collections.Counter to count how many times each word appears instead of using the dictionary method like the original code.

### Functions
I split the code into smaller functions so that each functions has their own job. This makes the code easier to read and find where mistakes happen.

## YouTube Link:

https://www.youtube.com/watch?v=mqiqM7MGKXU
