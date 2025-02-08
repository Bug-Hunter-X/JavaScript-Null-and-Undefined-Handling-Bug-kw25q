# JavaScript Null and Undefined Handling Bug

This repository demonstrates a common bug in JavaScript related to the handling of null and undefined values.

The `foo` function is designed to add two numbers. However, it only explicitly checks for null values, resulting in unexpected behavior when one or both inputs are undefined.

## Bug Description

The provided code does not distinguish between null and undefined inputs, leading to potential errors when undefined values are passed as arguments.  This is a subtle bug that can be difficult to track down if not properly addressed.

## Solution

The solution provided adds a check for undefined inputs, ensuring that the function handles both null and undefined values appropriately.  It also improves code readability and maintainability by using a more concise approach.

## How to reproduce:

1. Clone this repository
2. Open `bug.js` to observe the flawed code
3. Open `bugSolution.js` to see the corrected code