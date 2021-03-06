---
title: MD004 - Unordered list style
tags:  [bullet, ul]
alias: ul-style
---

Parameters: style ("consistent", "asterisk", "plus", "dash"; default "consistent")

This rule is triggered when the symbols used in the document for unordered
list items do not match the configured unordered list style:

    * Item 1
    + Item 2
    - Item 3

To fix this issue, use the configured style for list items throughout the
document:

    * Item 1
    * Item 2
    * Item 3

Note: the configured list style can be a specific symbol to use (asterisk,
plus, dash), or simply require that the usage be consistent within the
document.

