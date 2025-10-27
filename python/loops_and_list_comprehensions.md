### ELI5
Loops repeat an action over and over — like checking each card in a deck. A list comprehension is a faster way to write that same loop in one short line.

### Grown-Up
Python’s `for` loops iterate over sequences. List comprehensions provide a concise syntax for generating new lists from existing ones:
```python
squares = [x**2 for x in range(10)]
```
They are more readable and efficient for simple transformations.
