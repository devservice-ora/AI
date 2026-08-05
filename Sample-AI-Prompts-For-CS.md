# C++ Code Review Prompts Collection

## Overview

This document contains a curated list of example prompts designed for CS102 students to effectively seek AI feedback on C++ assignments. The prompts focus on code readability, parallel array safety, output formatting, control flow logic, and rubric-aligned evaluations—guiding students to get constructive hints, logic explanations, and structural feedback without revealing completed code solutions.
 
> *Note: For prompts requiring code or rubric files, please attach your relevant file (`[attach file here]`) when submitting the prompt to the AI tutor.*

**See also**: [Common AI Prompt Examples](https://github.com/devservice-ora/AI/blob/main/Common%20AI%20prompt%20examples.md)

---

## 1. General Code & Structure Review

**From My CS Student**:
> Hi Professor, I read your article, and I think the point about understanding the fundamentals of AI was very interesting > because it connects to how we are learning to program. Just as someone cannot truly understand C++ by copying code
> without understanding the concepts behind it, using AI effectively requires more than just asking it for answers. This
> is especially important when using AI as a peer reviewer because the quality of the feedback depends on the questions we
> ask and our ability to understand and evaluate the suggestions.
>
> When I used AI to review my lab assignment, I did not simply ask it to rewrite my code. Instead, I provided specific
> steps on readability and efficiency, and explained the reasoning behind each change. The feedback helped me identify
> improvements, but I still had to understand why those changes made the program better before I applied them. I think this
> shows that AI is most useful when it supports our learning rather than replacing the process of understanding programming
> concepts.


> This is my final working code to address these project parameters. How can I improve my code? Improvements in either readability or to more closely mirror a real banking statement regarding the instructions. Please address any logical and all other flaws.

> How can I pass variables by reference in this function?

> Check my variable types and arithmetic logic to prevent issues with integer division by using the appropriate floating-point variables.

> Please review my basic C++ code for syntax errors and ensure that my function and output streams are structured correctly.

> Identify issues in my code and provide hints for fixing them without rewriting it.

> Check out my attached file! I'm looking for tips on how to make my code more user-friendly and easier to follow. Any suggestions?

> How to indent the `cout` to the left using `setw`?

> How can I make my conditional statements more efficient? Can you suggest ways to improve the organization of my source code?

> Give me a few branching examples and explain why each condition is true or false.”

> Act as a peer reviewer for my C++ code. Trace my decision tree with the following test inputs: negative numbers, zero, and upper-boundary numbers. Point out any logical gaps or overlapping conditions where a value might trigger the wrong branch, but do not rewrite the code

> Review my C++ code for syntax errors and readability, but strictly constrain your suggestions to basic control structures (if/else, loops) and standard raw arrays. Do not suggest advanced C++ features or library functions outside of <iostream> and <iomanip>.

> Check my loop logic for accessing parallel arrays and confirm every array uses the same index consistently, and flag any risk of writing past the array bounds when I append an extra record.

> How should I pass variables by reference in this function?", "How can I validate user input using a while loop?", or "How can I format my output using setw() and setprecision()?

> Review my parallel array code for safety against out-of-bounds indexing and check if my <iomanip> formatting aligns the columns cleanly.

> Review my C++ branching program and improve its variable names, constants, readability, and output formatting without changing the original logic

> Review my C++ savings-account loop program for input validation, variable scope, repeated calculations, and readability while keeping the required calculations unchanged.

> Examine my function parameter passing, verify that reference variables are used correctly to update state, and suggest stream validation improvements.

> Check my variable types and arithmetic logic to ensure I am avoiding integer division traps and using appropriate floating-point variables.

> Review my code without changing its functionality. First, suggest improvements for organization and readability. Then, identify any unnecessary or repetitive code that could be condensed into a single function. Finally, explain the reasoning behind your suggestions and how they would enhance my code.

> Suggestions for making my code easier to follow include avoiding vague variable names and considering the use of ternary operators to simplify if-else statements.

---

## 2. Parallel Arrays & Bounds Checking

> Review my beginner-level C++ program that uses parallel arrays for input validation, checks for out-of-bounds conditions, avoids repeated calculations, improves readability, and ensures logical flow without altering the required calculations.

> Review my loop logic for accessing parallel arrays and ensure that all arrays use the same index consistently. Also, identify any risks of writing beyond the array bounds when I add an extra record.

> Review my loop logic accessing parallel arrays. Verify that every array uses the same variable index consistently across all operations. Highlight any risk of accessing an array out of bounds or using an array size variable incorrectly.

> Review my loop and suggest ways to optimize performance and reduce unnecessary calculations.

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

> Review my C++ savings account simulation. Suggest improvements for repetitive output formatting using helper functions and ways to prevent invalid inputs, like negative numbers or letters, from causing crashes.

> How can I format the output more neatly and minimize repetitive code?

---

## 4. Control Flow, Logic & Decision Trees

> Check my boundary checks for fee calculations and identify any unreachable comparisons in my if-else chain.

> Review my C++ code and identify any confusing variable names or loop conditions. Explain my program's logic step by step without providing code solutions.

> Please review my C++ loop implementation for two specific aspects:
> 1. Are all accumulator variables properly initialized before entering the loop?
> 2. Is there any input combination that could potentially lead to an infinite loop or an off-by-one iteration? Please explain any issues you find.

> Review my C++ code and analyze the decision tree using these test inputs: negative numbers, zero, and upper-boundary numbers. Identify any logical gaps or overlapping conditions that could lead to incorrect branches, but do not rewrite the code.

> Review my C++ code for syntax errors and readability. Focus only on basic control structures (if/else, loops) and standard raw arrays. Do not suggest advanced features or external library functions.

> Review my classes and suggest ways to make them better comply with C++ best practices.

---

## 5. Optimization & Rubric Evaluation

> Analyze my code as if you were a professor grading it, using this rubric.

> Review my code without changing the original functionality. Can you first suggest ways I can improve the organization and readability of the code?

> Review my code using the following steps:
> 1. Check readability and suggest improvements without changing functionality.
> 2. Identify repeated calculations and any unnecessary code or variables that can be made more efficient.
> 3. Explain the benefits of each suggested improvement.

> Review my C++ savings account program for readability, efficiency, and structure. Suggest improvements without altering its functionality or output format, and explain the benefits of each suggestion.
