# Unexpected Behavior with CSS `calc()` Function

This repository demonstrates two uncommon issues that can arise when using the `calc()` function in CSS:

1. **Unexpected Results from Percentage Calculations:** The order of operations and the timing of calculations can lead to unexpected results when combining percentages and other units in `calc()`.  This is particularly problematic when the containing element's dimensions are not yet determined.
2. **Incorrect Comment Placement:**  Placing comments within the `calc()` expression itself is invalid CSS and causes parsing errors.

The `bug.css` file contains examples illustrating these issues, while `bugSolution.css` provides corrected versions.

## How to reproduce:

1. Clone this repository.
2. Open `bug.html` (or create a simple HTML file linking to `bug.css`) in your browser.
3. Observe the unexpected behavior.
4. Switch to `bugSolution.css` to see the corrected version.