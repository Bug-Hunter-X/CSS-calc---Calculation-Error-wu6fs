# CSS calc() Calculation Error

This repository demonstrates a common error when using the `calc()` function in CSS. The issue arises from omitting an arithmetic operator between different units within the calculation.

## Bug Report
The `bug.css` file contains the erroneous CSS code. The `width` property uses `calc()` incorrectly, leading to unexpected results in the browser. 

## Solution
The `bugSolution.css` file provides the corrected CSS code.  The solution involves adding a plus or minus operator between the percentage and pixel values. 
