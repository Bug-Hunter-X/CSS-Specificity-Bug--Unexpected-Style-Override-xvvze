# CSS Specificity Bug

This repository demonstrates a common CSS issue related to specificity.  A more specific selector unintentionally overrides the intended style of a less specific selector. The `bug.css` file shows the problem, while `bugSolution.css` provides the fix.

## Bug Description:

The issue is caused by the unintended style override due to higher specificity selectors.  Understanding the order of precedence (inline > ID > class > element) is key to solving this problem.

## Solution:

The solution involves carefully reviewing the selectors and adjusting their specificity to ensure the intended styles are applied.