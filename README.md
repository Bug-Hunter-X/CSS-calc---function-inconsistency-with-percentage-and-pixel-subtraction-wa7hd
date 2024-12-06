# CSS calc() Inconsistency with Percentage and Pixel Subtraction

This repository demonstrates an uncommon issue related to the CSS `calc()` function when combining percentage and fixed-unit values.  Specifically, it highlights inconsistent behavior across browsers when subtracting pixels from a percentage width.

The `bug.css` file contains the problematic CSS code. The `bugSolution.css` file offers potential workarounds and best practices.

The issue stems from the way browsers parse and evaluate the `calc()` expression.  Different interpretations can lead to varying results across different browser engines.

**Key Points:**

* The problem arises when mixing percentage and fixed-unit values (e.g., `px`, `em`, `rem`) within the `calc()` expression.
* Inconsistent rendering may occur across different browsers.
* Workarounds involve using alternative calculation methods or more precise unit handling.

This repository serves as a practical example and encourages careful consideration of unit consistency when working with the CSS `calc()` function.