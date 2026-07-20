# Longest Valid Parentheses

## Problem
Given a string containing only '(' and ')', return the length of the longest valid (well-formed) parentheses substring.

## Approach
- Used Stack.
- Push -1 initially as a base index.
- Traverse the string once.
- Update the maximum valid length whenever a matching pair is found.

## Time Complexity
O(n)

## Space Complexity
O(n)

Language: Java
