# CSS `calc()` Function Error

This repository demonstrates a common error in using the `calc()` function in CSS. The error arises from missing spaces between operators and operands within the calculation.

## The Problem
Incorrect spacing within the `calc()` function can lead to unexpected layout results.  For instance,  `width:calc(100%-10px);` will not be interpreted correctly.  

## The Solution
Ensure that there are spaces between the operators and operands in the `calc()` function.  The correct syntax is `width: calc(100% - 10px);`

See `bug.css` for the incorrect code and `bugSolution.css` for the corrected version.