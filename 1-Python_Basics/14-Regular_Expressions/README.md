# Python Regular Expressions

## Overview

This document provides an overview of **regular expressions** in Python, a powerful tool for string searching and manipulation. Regular expressions allow you to match patterns in text and perform complex searches and modifications efficiently.

### What are Regular Expressions?

Regular expressions (regex) are sequences of characters that form a search pattern. They are commonly used for tasks such as searching, validating, and replacing text in strings.

### Basic Syntax

In Python, you can use the `re` module to work with regular expressions. Here are some of the basic functions:

- **`re.search()`**: Searches for a pattern in a string and returns a match object if found.
- **`re.match()`**: Checks for a match only at the beginning of the string.
- **`re.findall()`**: Returns a list of all non-overlapping matches in the string.
- **`re.sub()`**: Replaces occurrences of a pattern with a specified string.

### Common Patterns

- **`.`**: Matches any character except a newline.
- **`^`**: Matches the start of the string.
- **`$`**: Matches the end of the string.
- **`*`**: Matches 0 or more repetitions of the preceding pattern.
- **`+`**: Matches 1 or more repetitions of the preceding pattern.
- **`?`**: Matches 0 or 1 repetition of the preceding pattern.
- **`[abc]`**: Matches any character in the brackets.
- **`( )`**: Groups patterns together.

### Example Usage

Here's a simple example demonstrating how to use regular expressions in Python:

```python
import re

text = "The rain in Spain"
pattern = r"\bain\b"

# Search for the pattern
if re.search(pattern, text):
    print("Pattern found!")
else:
    print("Pattern not found.")
git clone https://github.com/Sadam-Barkat/14-Regular_Expressions.git
