# Uncommon CSS Bugs: Specificity and Inheritance

This repository demonstrates some less common but potentially tricky CSS bugs related to specificity and inheritance.  These bugs can be challenging to diagnose if you're not aware of the subtleties involved.

## Bug Scenarios

The `bug.css` file contains examples of unexpected behavior caused by:

1. **CSS Specificity:** The interaction between ID selectors, class selectors, and element selectors can lead to unexpected results if not carefully considered.
2. **Inheritance:**  Unexpected inheritance of styles can cause inconsistencies if not handled properly.  The `!important` flag can also be misused causing issues in larger projects.

## Solutions

The `bugSolution.css` file provides solutions to the problems identified in `bug.css`.  These solutions focus on clear and maintainable CSS practices to avoid these pitfalls.

## How to Use

1. Clone the repository.
2. Open the HTML files in a web browser to see the bugs in action.
3. Compare the `bug.css` file to the `bugSolution.css` file to understand how to resolve the issues.