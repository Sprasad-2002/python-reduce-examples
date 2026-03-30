# Python Reduce Function Examples

This repository contains examples of Python's `reduce()` function.

## Files
- ex1.py - Basic reduce example
- ex2.py - Advanced reduce usage

## What is reduce?
reduce() is used to apply a function cumulatively to items of a sequence.

## Example
```python
from functools import reduce

nums = [1, 2, 3, 4]
result = reduce(lambda x, y: x + y, nums)
print(result)  # Output: 10
