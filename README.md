# TypeScript Type Error: Argument of type 'string[]' is not assignable to parameter of type 'string'

This repository demonstrates a common TypeScript error: passing an array of strings to a function expecting a single string.

The `bug.ts` file contains the erroneous code. The `bugSolution.ts` file shows how to correct the error.

## How to reproduce the bug

1. Clone this repository.
2. Navigate to the repository directory.
3. Compile and run `bug.ts` using the TypeScript compiler (tsc) and node.
4. Observe the type error.

## Solution

The solution involves either modifying the function to accept an array or modifying the input to provide a single string.  The `bugSolution.ts` file provides the corrected implementation.