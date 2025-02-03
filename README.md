# Python Bug: ZeroDivisionError in Average Calculation

This repository demonstrates a common bug in Python involving the `ZeroDivisionError` when calculating the average of a list of numbers.  The bug occurs when attempting to calculate the average of an empty list, which leads to division by zero.  The solution involves adding a check to handle this edge case.

**Bug:** The original `calculate_average` function does not explicitly handle the case where the input list is empty, leading to a `ZeroDivisionError`.

**Solution:** The improved `calculate_average` function now includes a check for an empty list. If the list is empty, it returns 0; otherwise, it proceeds with the average calculation.
