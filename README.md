# CSS Specificity Conflicts
This example demonstrates a common issue in CSS: unexpected styling due to specificity conflicts.  Two selectors target the same element, but one has higher specificity and overrides the other.

## Problem
The styles applied to the `p` element aren't as expected due to conflicting selectors. The `p` element within the `div` has a higher specificity than the general `p` selector, overriding the color style.

## Solution
This solution uses the `!important` declaration to resolve the conflict.  However, using `!important` should be done sparingly and only when necessary, as it can decrease the maintainability of your CSS.

Alternatively, more specific selectors can be used to address the problem without using `!important`.
