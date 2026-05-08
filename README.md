# Exercise 02 — Conditionals & Control Flow

## What you'll learn
- `if`, `elif`, `else`
- Comparison operators: `==`, `!=`, `<`, `>`, `<=`, `>=`
- Logical operators: `and`, `or`, `not`
- Nested conditions

## Your task

Open `solution.py` and implement each function based on its docstring.

## How to run the tests

```bash
pytest
```

Make all tests pass ✅.

## Hints
- Python uses indentation (4 spaces) to define blocks — no curly braces!
- You can chain comparisons: `0 < x < 100`
- `elif` is short for "else if"

## Example

```python
def classify(score):
    if score >= 90:
        return "A"
    elif score >= 75:
        return "B"
    else:
        return "C"
```
