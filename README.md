# JavaScript Division by Zero Bug

This repository demonstrates a common JavaScript error: division by zero. The `bug.js` file contains a function with a potential division by zero error. The `bugSolution.js` file provides a corrected version.

## Bug Description

The `myFunction` in `bug.js` doesn't properly handle cases where the second argument (`b`) is zero, resulting in a runtime error. 

## Solution

The solution in `bugSolution.js` adds a check to prevent division by zero.  It returns an appropriate value (or throws an error depending on your preferred handling) when this condition is met.