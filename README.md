# CppME_Chapter6

This repository contains the sample programs for Chapter 6 of "C++ Programming Made Easy." The examples focus on fundamental C++ programming concepts such as arithmetic operations, relational operators, and basic user input/output.

## Repository Structure

- `CppME_Chapter6.cpp` — the main starter program for the chapter
- `CppME_Chapter6.slnx` — solution file for the Visual Studio project
- `CppME_Chapter6.vcxproj` — main project configuration
- `CppME_Chapter6.vcxproj.filters` — Visual Studio filter configuration
- `CppME_Chapter6_Example6.5/` — example demonstrating arithmetic operators
- `CppME_Chapter6_Example6.8/` — example demonstrating relational operators
- `CppME_Chapter6_Example6.15/` — example using arithmetic operations with user input

## Included Examples

### Example 6.5: Basic Arithmetic
Located in `CppME_Chapter6_Example6.5/`.

This program demonstrates:
- addition
- subtraction
- multiplication
- division
- modulus

### Example 6.8: Relational Operators
Located in `CppME_Chapter6_Example6.8/`.

This program compares values using:
- `==`
- `!=`
- `>`
- `<`
- `>=`
- `<=`

### Example 6.15: Arithmetic with User Input
Located in `CppME_Chapter6_Example6.15/`.

This program asks the user for two numbers and displays the results for:
- addition
- subtraction
- multiplication
- division

## Building and Running

### With Visual Studio

1. Open `CppME_Chapter6.slnx` in Visual Studio.
2. Build the solution.
3. Run the project from the IDE.

### From the Command Line

Compile the main program with:

```bash
g++ CppME_Chapter6.cpp -o CppME_Chapter6
./CppME_Chapter6
```

To compile one of the chapter examples:

```bash
g++ CppME_Chapter6_Example6.5/CppME_Chapter6_Example6.5.cpp -o Example6_5
./Example6_5
```

## Notes

This repository is intended for beginner C++ learners and serves as a practical collection of chapter-based sample programs. Each example is designed to be easy to understand and modify for experimentation.
