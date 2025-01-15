# TypeScript Type Mismatch Bug

This repository demonstrates a common TypeScript error: type mismatch.  The `add` function expects two numbers, but the example attempts to pass a string. TypeScript's type system catches this error during compilation, preventing runtime failures. This is a simple example showcasing TypeScript's strength in catching common type-related errors.

## Bug
The `bug.ts` file contains the code with the type mismatch error. 

## Solution
The `bugSolution.ts` file demonstrates the corrected code, ensuring that only numbers are passed to the function.