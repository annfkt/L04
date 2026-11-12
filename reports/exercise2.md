# Bug reports for exercise2.py

Line: 12
Problem: clamp limits x to low twice, but the docstring says "x, limited to the range from low to high". It should use min(x, high) and max(low, ...) correctly.
Example: clamp(3, 1, 5) returns 1, expected 3.
Fix: return max(low, min(x, high))
