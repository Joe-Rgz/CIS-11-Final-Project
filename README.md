# CIS-11-Final-Project
Scores Calculator 

# Test Score Calculator - LC-3 Assembly Project

## Overview

The **Test Score Calculator** is an LC-3 Assembly program that allows a user to enter five test scores. The program calculates and displays the minimum score, maximum score, average score, and the letter grade equivalent.

This project was created for a CIS 11 Assembly Language course and demonstrates the use of arithmetic operations, memory storage, branching, loops, subroutines, and console input/output in LC-3 Assembly.

---

## Team Information

**Team Name:** Team Stack  

**Team Members:**
- Joseph Rodriguez - Documentation and coordinator
- Lucas Vida - Coding, Debugging, and Testing

---

## Program Features

The program performs the following tasks:

- Prompts the user to enter 5 test scores
- Stores the scores in memory
- Finds the minimum score
- Finds the maximum score
- Calculates the average score
- Determines the letter grade equivalent
- Displays the results to the console

---

## Grading Scale

| Score Range | Letter Grade |
|------------|--------------|
| 90 - 100   | A            |
| 80 - 89    | B            |
| 70 - 79    | C            |
| 60 - 69    | D            |
| 0 - 59     | F            |

---

## Technologies Used

- LC-3 Assembly Language
- LC-3 Simulator
- Assembly programming concepts:
  - Registers
  - Memory addresses
  - Branching
  - Loops
  - Subroutines
  - TRAP routines
  - Input and output operations

---

## Project Requirements

This program satisfies the following project requirements:

1. Contains appropriate addresses such as:
   - `.ORIG`
   - `.FILL`
   - Arrays
   - Input storage
   - Output strings

2. Displays the following values in the console:
   - Minimum score
   - Maximum score
   - Average score
   - Letter grade equivalent

3. Uses appropriate labels and comments throughout the code.

4. Uses appropriate LC-3 instructions for:
   - Arithmetic operations
   - Data movement
   - Conditional operations
   - Branching

5. Includes two or more subroutines and implements subroutine calls.

---

## How the Program Works

1. The program begins at the starting memory address using `.ORIG`.
2. The user is prompted to enter five test scores.
3. Each score is stored in memory.
4. The program compares the scores to find the minimum and maximum values.
5. The scores are added together.
6. The total is divided by 5 to calculate the average.
7. The average is compared against the grading scale.
8. The program displays the minimum score, maximum score, average score, and letter grade.
9. The program ends using `HALT`.

---

## Example Output

```text
Enter score 1: 85
Enter score 2: 90
Enter score 3: 78
Enter score 4: 92
Enter score 5: 88

Minimum Score: 78
Maximum Score: 92
Average Score: 86
Letter Grade: B
