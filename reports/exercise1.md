# Bug reports for exercise1.py

Line: 3
Problem: is_even returns True for odd numbers, but the docstring says "true for even numbers".
Example: is_even(3) returns True, expected False.
Fix: return n % 2 == 0

Line: 8
Problem: rectangle_area returns the sum of width and height, but the docstring says "area of a rectangle".
Example: rectangle_area(4, 5) returns 9, expected 20.
Fix: return width * height

Line: 12
Problem: double returns n + 2, but the docstring says "twice the number n".
Example: double(5) returns 7, expected 10.
Fix: return n * 2
