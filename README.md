# Unexpected Null Behavior in JavaScript Function

This repository demonstrates a common error in JavaScript related to handling null values and provides a solution.

## Bug Description

The provided JavaScript function `foo` adds two numbers together.  However, it doesn't explicitly handle potential null values passed as arguments, leading to unexpected behavior.

## Solution

The improved version of the `foo` function handles null values explicitly, returning null when either or both input values are null.  This prevents potential errors and improves the overall robustness of the code.

## Usage

1. Clone the repository.
2. Run the `bug.js` file to see the original error.
3. Then run the `bugSolution.js` file to see the solution.