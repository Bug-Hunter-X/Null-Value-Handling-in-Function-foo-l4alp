# Null Value Handling in JavaScript Function

This repository demonstrates a common error in JavaScript: unexpected behavior when null values are passed as arguments to a function.

The `bug.js` file shows the initial function implementation, which does not explicitly handle null values, leading to potential errors.

The `bugSolution.js` file shows the improved implementation which addresses this issue and handles null values gracefully.

## Bug Description
The function `foo` doesn't handle null values appropriately, potentially resulting in unexpected behavior or runtime errors.

## Solution
The improved function `foo` now checks for null values using strict equality (`===`) before proceeding with its calculations. If either `a` or `b` is null, the function returns null, preventing errors and providing a more robust solution.  This approach maintains clarity and allows for explicit null handling.