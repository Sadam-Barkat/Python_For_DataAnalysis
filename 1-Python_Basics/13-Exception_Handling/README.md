# Python Exception Handling

## Overview

This document provides an overview of **exception handling** in Python, a mechanism that allows you to manage errors gracefully without crashing your program.

### What is Exception Handling?

Exception handling is a way to respond to the occurrence of exceptions—errors that occur during the execution of a program. It allows you to write code that can handle errors gracefully, ensuring that your program continues to run or provides a useful error message.

### Basic Syntax

The basic syntax for exception handling in Python involves the `try`, `except`, and optionally, `finally` blocks:

```python
try:
    # Code that may raise an exception
    result = 10 / 0
except ZeroDivisionError:
    # Code that runs if a ZeroDivisionError occurs
    print("You can't divide by zero!")
finally:
    # Code that runs no matter what
    print("Execution complete.")
git clone https://github.com/Sadam-Barkat/13-Exceptional_Handling.git
