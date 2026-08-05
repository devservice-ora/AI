# C++ Code Review Prompts Collection

## Overview

This document contains a curated list of example prompts designed for CS102 students to effectively seek AI feedback on C++ assignments. The prompts focus on code readability, parallel array safety, output formatting, control flow logic, and rubric-aligned evaluations—guiding students to get constructive hints, logic explanations, and structural feedback without revealing completed code solutions.
 
> *Note: For prompts requiring code or rubric files, please attach your relevant file (`[attach file here]`) when submitting the prompt to the AI tutor.*

**See also**: [Common AI Prompt Examples](https://github.com/devservice-ora/AI/blob/main/Common%20AI%20prompt%20examples.md)

---

## 1. General Code & Structure Review

> This is my final working code to address these project parameters. How can I improve my code? Improvements in either readability or to more closely mirror a real banking statement regarding the instructions. Please address any logical and all other flaws.

> How can I pass variables by reference in this function?

> Check my variable types and arithmetic logic to prevent issues with integer division by using the appropriate floating-point variables.

> Please review my basic C++ code for syntax errors and ensure that my function and output streams are structured correctly.

> Identify issues in my code and provide hints for fixing them without rewriting it.

> Check out my attached file! I'm looking for tips on how to make my code more user-friendly and easier to follow. Any suggestions?

> How to indent the `cout` to the left using `setw`?

---

## 2. Parallel Arrays & Bounds Checking

> Review my beginner-level C++ program that uses parallel arrays for input validation, checks for out-of-bounds conditions, avoids repeated calculations, improves readability, and ensures logical flow without altering the required calculations.

> Review my loop logic for accessing parallel arrays and ensure that all arrays use the same index consistently. Also, identify any risks of writing beyond the array bounds when I add an extra record.

> Review my loop logic accessing parallel arrays. Verify that every array uses the same variable index consistently across all operations. Highlight any risk of accessing an array out of bounds or using an array size variable incorrectly.

> Check my parallel array code for safety against out-of-bounds indexing and ensure my `<iomanip>` formatting aligns the columns neatly.

> Review my code C++ program:
> 1. Review my parallel arrays and verify that every array uses the same index consistently throughout the program.
> 2. Check for any off-by-one errors.
> 3. Check for any incorrect `total_records` updates.
> 4. Check for any places where an array could be accessed out of bounds.
> 5. How can I use functions to make my code shorter and more efficient?

---

## 3. Formatting, Output & Helper Functions

> Provide a suggestion for creating a helper function to handle repeated `cout` formatting and verify if the input validation effectively rejects negative numbers and non-numeric input.

> Review my C++ program to see if my variable names accurately represent their stored values. Additionally, identify any instances where my output columns may not align for a grader using different input values.

> This is a C++ program. Review my ledger output and suggest improvements to enhance the table's readability while maintaining all necessary information and calculations.

> Please review my C++ savings account simulation. Suggest improvements for repetitive output formatting using helper functions and ways to prevent invalid inputs, like negative numbers or letters, from causing crashes.

---

## 4. Control Flow, Logic & Decision Trees

> Check my boundary checks for fee calculations and identify any unreachable comparisons in my if-else chain.

> Review my C++ code and identify any confusing variable names or loop conditions. Explain my program's logic step by step without providing code solutions.

> Please review my C++ loop implementation for two specific aspects:
> 1. Are all accumulator variables properly initialized before entering the loop?
> 2. Is there any input combination that could potentially lead to an infinite loop or an off-by-one iteration? Please explain any issues you find.

> Review my C++ code and analyze the decision tree using these test inputs: negative numbers, zero, and upper-boundary numbers. Identify any logical gaps or overlapping conditions that could lead to incorrect branches, but do not rewrite the code.

> Review my C++ code for syntax errors and readability. Focus only on basic control structures (if/else, loops) and standard raw arrays. Do not suggest advanced features or external library functions.

---

## 5. Optimization & Rubric Evaluation

> Analyze my code as if you were a professor grading it, using this rubric.

> Review my code without changing the original functionality. Can you first suggest ways I can improve the organization and readability of the code?

> Review my code using the following steps:
> 1. Check readability and suggest improvements without changing functionality.
> 2. Identify repeated calculations and any unnecessary code or variables that can be made more efficient.
> 3. Explain the benefits of each suggested improvement.

> Review my C++ savings account program for readability, efficiency, and structure. Suggest improvements without altering its functionality or output format, and explain the benefits of each suggestion.
