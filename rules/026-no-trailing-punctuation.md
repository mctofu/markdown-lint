---
title: MD026 - Trailing punctuation in header
tags:  [headers]
alias: no-trailing-punctuation
---

Parameters: punctuation (string; default ".,;:!?")

This rule is triggered on any header that has a punctuation character as the
last character in the line:

    # This is a header.

To fix this, remove any trailing punctuation:

    # This is a header

Note: The punctuation parameter can be used to specify what characters class
as punctuation at the end of the header. For example, you can set it to
`'.,;:!'` to allow headers with question marks in them, such as might be used
in an FAQ.


