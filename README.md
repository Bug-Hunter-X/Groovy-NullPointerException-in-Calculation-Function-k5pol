# Groovy NullPointerException in Calculation Function

This repository demonstrates a common error in Groovy: a `NullPointerException` occurring when performing arithmetic operations on variables that might be null.  The `calculate` function lacks proper null checks, causing unexpected behavior when null values are passed as arguments. The solution demonstrates how to efficiently handle null values to avoid this exception.

## Bug

The `bug.groovy` file contains a function that adds two numbers. However, it does not handle the case where either or both inputs are null, leading to a `NullPointerException`.

## Solution

The `bugSolution.groovy` file provides a corrected version that incorporates a null check to avoid this exception.  The solution employs a simple `if` statement to handle null values gracefully and provides a default return value of 0.
