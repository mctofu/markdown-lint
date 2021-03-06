---
title: MD009 - Trailing spaces
tags:  [whitespace]
alias: no-trailing-spaces
---

Parameters: br_spaces (number; default: 0)

This rule is triggered on any lines that end with whitespace. To fix this,
find the line that is triggered and remove any trailing spaces from the end.

The br_spaces parameter allows an exception to this rule for a specific amount
of trailing spaces used to insert an explicit line break/br element. For
example, set br_spaces to 2 to allow exactly 2 spaces at the end of a line.

Note: you have to set br_spaces to 2 or higher for this exception to take
effect - you can't insert a br element with just a single trailing space, so
if you set br_spaces to 1, the exception will be disabled, just as if it was
set to the default of 0.

