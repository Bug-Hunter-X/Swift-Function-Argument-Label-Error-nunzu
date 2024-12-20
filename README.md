# Swift Function Argument Label Error

This repository demonstrates a common error in Swift: omitting argument labels when calling functions with labeled parameters.

The `bug.swift` file contains code that showcases the error. The `bugSolution.swift` file provides the corrected version.

## Description

Swift's use of external and internal parameter names offers flexibility, but it's important to use argument labels correctly when calling functions to avoid ambiguity and compiler errors.

## Bug

The original code attempts to call the `calculateArea` function without providing the argument label for the `width` parameter, resulting in a compiler error.

## Solution

The solution demonstrates the correct usage of argument labels when calling the `calculateArea` function, ensuring that the compiler can correctly match the values to the appropriate parameters.