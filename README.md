# Unexpected String Concatenation in JavaScript

This example demonstrates a common JavaScript pitfall involving the '+' operator.  When used with a mix of numbers and strings, '+' performs string concatenation rather than numerical addition. This can lead to unexpected results if not handled carefully.

The `bug.js` file shows the problem.  The `bugSolution.js` file offers a corrected version.

## How to reproduce
1. Save the provided JavaScript code to a file named `bug.js`
2. Run the file using Node.js: `node bug.js`
3. Observe the unexpected output.

## Solution
Refer to `bugSolution.js` for a corrected version that uses `parseInt()` to ensure numerical addition.