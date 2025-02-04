# CSS Specificity Bug: Compound Selectors

This repository demonstrates a subtle but important bug related to CSS specificity and the use of compound selectors. The bug arises from the unexpected behavior of combining ID and class selectors in a single rule.

## Bug Description

The `bug.css` file contains a CSS snippet that showcases the unexpected override of styles due to the specificity of compound selectors. An element with both an ID and a class is styled inconsistently.

## Solution

The `bugSolution.css` file provides a corrected version of the CSS code that addresses the specificity issue. This is achieved by carefully considering the order and structure of the CSS rules to ensure the desired styling is applied correctly.

## How to Reproduce

1. Clone the repository.
2. Open `bug.html` (or create your own HTML file containing the relevant elements).
3. Link to the `bug.css` file in your HTML.
4. Observe the unexpected styling behavior.
5. Replace `bug.css` with `bugSolution.css` and observe the correct styling.