# Strings in Python

This repository contains a Python script that demonstrates various operations and properties of strings in Python. It serves as a beginner-friendly guide to understanding how to work with strings effectively.

## Features

- **String Initialization**: Examples of how to create strings using single, double, and triple quotes.
- **String Concatenation**: Combine multiple strings using the `+` operator and formatted strings (f-strings).
- **String Indexing and Slicing**: Access individual characters and substrings.
- **String Immutability**: Explanation of why strings in Python cannot be modified directly.
- **String Functions**: Demonstrations of common string methods such as `replace`, `find`, `upper`, `lower`, `isdigit`, and `strip`.
- **Substring Operations**: Check if a substring exists and find its position within a string.
- **String Splitting**: Split a string into a list based on a delimiter.


### Expected Output
The script demonstrates various string operations and prints the results to the console. Each section is accompanied by comments explaining the code's purpose.

## Key Learnings

1. **String Basics**:
   - Strings are sequences of characters enclosed in quotes.
   - Strings are immutable; you cannot modify them in place.

2. **Indexing and Slicing**:
   - Use square brackets (`[]`) to access specific characters or substrings.
   - Negative indexing allows access to characters from the end of the string.

3. **Common String Functions**:
   - `replace`: Replace a substring with another substring.
   - `find`: Locate the position of a substring.
   - `upper` and `lower`: Change the case of a string.
   - `strip`: Remove leading and trailing whitespace.

4. **Formatted Strings**:
   - F-strings (introduced in Python 3.6) provide a clean way to embed variables within strings.

Check out the file: [Strings.ipynb](./Strings.ipynb)  
## Code Example

```python
# Concatenating strings
first_name = 'Maze'
last_name = 'Smith'
full_name = f"{first_name} {last_name}"
print(f"Full name: {full_name}")

# Using string functions
message = "    Hey! We have to leave now.  "
print(message.strip())
```
