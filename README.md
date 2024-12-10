# Unexpected ':nth-child' Selector Behavior in CSS

This repository demonstrates an uncommon issue related to the CSS `:nth-child` selector.  The `:nth-child` selector can be tricky, and this example shows how its behavior can be unexpected when used with dynamic content or in conjunction with other selectors.

## The Problem

The provided `bug.css` demonstrates a situation where applying `:nth-child` to a list with dynamically changing elements causes unexpected styling issues. The solution addresses the problem by using a more robust approach.

## Solution

The `bugSolution.css` file offers an alternative approach to achieve the desired styling, addressing the inconsistencies demonstrated in `bug.css`.

This solution is more robust and less susceptible to changes in the HTML structure or the number of list items.