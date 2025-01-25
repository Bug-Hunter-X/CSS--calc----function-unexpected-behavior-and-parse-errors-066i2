# CSS `calc()` Function Issues

This repository demonstrates some common issues that can arise when using the CSS `calc()` function.  The `bug.css` file contains code that exhibits unexpected behavior due to incorrect usage of `calc()`. The `bugSolution.css` file provides corrected code that addresses these issues.

**Issues:**

* **Unit Inconsistency:** Mixing percentages and pixels without careful consideration can lead to unexpected results. 
* **Operator Precedence:** Incorrect operator precedence can cause the calculation to be evaluated in an unintended way.
* **Missing Spaces:** Forgetting to include spaces around operators within the `calc()` function can lead to parse errors.

**Solutions:**

* **Consistent Units:** Ensure that you use consistent units throughout your `calc()` expression. If mixing units, be aware of how they interact.
* **Parentheses:**  Use parentheses to explicitly define operator precedence.
* **Spacing:**  Always include spaces around the operators (+, -, *, /) in your `calc()` expression.