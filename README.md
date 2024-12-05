# JavaScript Null or Undefined Handling

This repository showcases a common JavaScript error related to handling null or undefined values and provides a solution.  The `bug.js` file contains code with a potential issue, while `bugSolution.js` demonstrates a robust solution.

## Problem

The provided code snippet demonstrates a function `foo` that adds two numbers.  However, it lacks proper handling of null or undefined values passed as arguments.  This can lead to unexpected behavior or runtime errors (e.g., `TypeError`).

## Solution

The solution in `bugSolution.js` explicitly checks for null or undefined values using strict equality (`===`) before performing the addition. If either value is null or undefined, it returns 0 to prevent errors and ensures predictable behavior.