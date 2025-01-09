# Loops in Python  

This repository contains a Python script that demonstrates the use of `for` loops in Python. It covers various practical applications, including iteration over lists, using the `zip` and `enumerate` functions, and integrating logical operations like `if` and `break`. This guide is ideal for beginners who want to master looping constructs in Python.  

---

## Features  

- **Basic Iteration**: Demonstrates iterating through lists using a `for` loop.  
- **Threshold Check**: Analyzing sales data to compare values against a defined threshold.  
- **Zip Function**: Combines two lists (e.g., months and sales data) for simultaneous iteration.  
- **Range Function**: Illustrates looping over index values and using those indices for operations.  
- **Enumerate Function**: Provides cleaner, indexed iterations over a list.  
- **Conditional Statements in Loops**:  
  - Use of `if`, `else`, `break`, and `continue` within loops.  
  - Skipping even numbers in a range using `continue`.  
- **Practical Applications**: Includes real-world scenarios like calculating total expenses with and without loops.  
- **Nested Operations**: Demonstrates complex logic inside a loop using conditions and mathematical operations.  

---

## Expected Output  

The script showcases multiple loop operations and prints results to the console. Each section is complemented by detailed comments explaining the purpose and functionality of the code.  

---

## Key Learnings  

### Basics of For Loops:  
- Loops allow iterating over collections like lists, tuples, and strings.  
- Use a `for` loop when the number of iterations is known beforehand.  

### Logical Operations:  
- Use `if` and `else` for condition-based execution within loops.  
- Use `break` to exit a loop prematurely and `continue` to skip to the next iteration.  

### Built-In Functions for Loops:  
- **`range()`**: Generate a sequence of numbers for indexed iteration.  
- **`zip()`**: Iterate over multiple lists in parallel.  
- **`enumerate()`**: Access both the index and value in a loop for better readability.  

### Practical Applications:  
- **Total Expense Calculation**: Comparing traditional and loop-based implementations.  
- **Threshold Analysis**: Checking sales values against a defined threshold.  
- **Filtering Values**: Skipping specific elements (e.g., even numbers) during iteration.  
Check out the file: [For-condition.ipynb](./For-condition.ipynb)  ---


## Code Example  

```python
# Basic iteration through a list
monthly_sales = [42, 38, 33, 38, 40, 45]
threshold = 35

# Threshold comparison
for sales_amount in monthly_sales:
    if sales_amount < threshold:
        print(f"Sales amount {sales_amount} is below the threshold")
        break
    else:
        print(f"Sales amount {sales_amount} is above the threshold")

# Using zip for parallel iteration
months = ["Jan", "Feb", "March", "April", "May", "June"]
for sales_amount, month in zip(monthly_sales, months):
    if sales_amount < threshold:
        print(f"Sales amount {sales_amount} is less than the threshold in {month}")
        break
    else:
        print(f"Sales amount {sales_amount} is greater than the threshold in {month}")

# Skipping even numbers using continue
for i in range(1, 11):
    if i % 2 == 0:
        continue
    print(i)

# Using enumerate for indexed iteration
expenses = [1200, 1300, 1500, 1700]
total_expense = 0
for i, expense in enumerate(expenses):
    print(f"Month {i+1}, Expense: {expense}")
    total_expense += expense
print("Total expense:", total_expense)
