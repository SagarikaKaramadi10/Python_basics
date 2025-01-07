# Conditional Statements in Python

This repository provides a comprehensive guide to using conditional statements (`if`, `elif`, and `else`) in Python. The included Jupyter Notebook demonstrates various use cases with clear examples and explanations.

## Insights into the `if` Condition

Conditional statements are a fundamental part of programming, allowing you to control the flow of your code based on specific conditions.

### Key Insights

#### Definition
- The `if` statement evaluates a condition.
- If the condition is `True`, the associated block of code is executed.

# Features

## Notebook Highlights
This repository covers the following key aspects of conditional statements:

- **Basics of Conditional Statements**: Learn the foundational concepts of `if`, `elif`, and `else` statements in Python.
- **Practical Examples**: Reinforce your understanding through various use cases:
  - Checking for even or odd numbers.
  - Using the ternary operator for concise conditions.
  - Testing membership within lists.
  - Classifying states by country.
Check out the file: [If-condition.ipynb](./If-condition.ipynb)  
---

## Example Code

### Classifying States
This example demonstrates how to classify states based on membership in a predefined list:
```python
# Example: Classifying states
India = ["Karnataka", "Maharashtra", "UP", "Gujarat"]
state = input("Enter a state: ")

if state in India:
    print(f"{state} is in India")
else:
    print(f"{state} is not in India")
