# Week 6 Assignment - Safe Functions

## Files

- safe_tools.py - Contains three safe functions for division, number conversion, and dictionary lookups.
- README.md - Describes the assignment and explains error handling.

## Why can the if check not catch abc on its own?

An if statement cannot automatically convert text into a number. When Python tries to convert "abc" using int(), it raises a ValueError. We use try and except ValueError to handle this error safely without crashing the program.
