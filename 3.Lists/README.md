# Lists in Python

This repository contains a Python script that demonstrates various operations and properties of lists in Python. It serves as a beginner-friendly guide to understanding how to work with lists effectively.

## Features

- **List Initialization**: Examples of how to create and access lists.
- **List Indexing and Slicing**: Access individual elements and subsets of a list.
- **Mutability**: Demonstration of adding, modifying, and removing elements.
- **Common List Methods**: Usage of methods like `append`, `remove`, `insert`, and `pop`.
- **List Combination**: Merging two lists into one.
- **Sorting**: Sorting elements in ascending and descending order.
- **Dynamic Updates**: Replacing elements dynamically in a list.

### Expected Output
The script demonstrates various list operations and prints the results to the console. Each section is accompanied by comments explaining the code's purpose.

## Key Learnings

1. **List Basics**:
   - Lists are sequences of elements enclosed in square brackets (`[]`).
   - Lists are **mutable**, allowing modification after creation.

2. **Indexing and Slicing**:
   - Use square brackets (`[]`) to access specific elements or subsets.
   - Negative indexing allows access to elements from the end of the list.

3. **Common List Methods**:
   - `append`: Add an element to the end of the list.
   - `remove`: Remove the first occurrence of a specified element.
   - `insert`: Insert an element at a specified index.
   - `pop`: Remove and return the last element (or element at a specified index).

4. **Sorting and Combining**:
   - Use `sort` to arrange elements in ascending or descending order.
   - Use the `+` operator to combine multiple lists.

Check out the file: [Lists.ipynb](./Lists.ipynb)  

## Code Example

```python
# Define a list of items
items = ["bread", "Pasta", "Coffee", "Veggies"]
print("Initial list of items:", items)

# Access the last item using negative indexing
print("Last item in the list:", items[-1])

# Access the first two items using slicing
print("First two items:", items[0:2])

# Add a new item to the end of the list
items.append("butter")
print("List after appending 'butter':", items)

# Remove an item from the list
items.remove("butter")
print("List after removing 'butter':", items)

# Insert an item at a specific position
items.insert(1, "butter")
print("List after inserting 'butter' at index 1:", items)

# Replace an item at a specific index
items[1] = "cola"
print("List after replacing item at index 1 with 'cola':", items)

# Replace multiple items starting from a specific index
items[3:] = ['almonds']
print("List after replacing items from index 3:", items)
