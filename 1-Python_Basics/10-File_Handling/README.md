# Python File Handling

## Overview

This document provides an overview of **file handling** in Python, which allows you to read from and write to files.

### What is File Handling?

File handling in Python refers to the process of reading and writing data to files on your computer. Python provides built-in functions and methods to facilitate this process.

### Opening a File

To work with a file, you first need to open it using the `open()` function:

```python
file = open('filename.txt', 'mode')
with open('filename.txt', 'r') as file:
    content = file.read()
    print(content)
with open('filename.txt', 'w') as file:
    file.write('Hello, World!\n')
git clone https://github.com/Sadam-Barkat/10-File_Handling.git
