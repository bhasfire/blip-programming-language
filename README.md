# Final Project: Custom Toy Programming Language

## Overview
In a university final project, I developed my own miniature toy programming language. This language, designed for simplicity in parsing, will consist of straight-line code including assignment and output statements. The primary focus is on applying C++ classes to create a program that is both modular and scalable.

## Language Specifications
- **Straight-line code**: Includes assignment and output statements.
- **Easy parsing**: The language is structured to be easily understandable by a computer program.
- **Resemblance**: It does not mimic any real programming language.

## Key Features
- **Minimal Starter Code**: Emphasis on self-designed data structures, algorithms, and overall approach.
- **Restrictions**: Limited use of standard libraries; mainly allowed are stack, string, map, and vector.

## The Blip Language
The language comprises four primary statements: `var`, `set`, `output`, and `text`.
- **Text Statements**: Display a text message on the screen.
- **Output Statements**: Display a number, which is the result of evaluating a Blip expression.
- **Var Statements**: Initialize a new variable.
- **Set Statements**: Assign a new value to an existing variable.

## Program Structure
- **Blip Programs**: Can include multiple statements per line; whitespace, tabs, and line breaks are non-significant.
- **Comments**: Supported using `//` but only between statements.
- **Variables and Memory**: Utilize a symbol table to track variable values.
- **Blip Expressions**: Use prefix expression syntax for operations (e.g., `+ 2 2` for addition).

## Input Parsing
- Provided `Input.cpp` and `Parse.h` files assist in reading Blip programs.
- **Tokens**: Defined as NUMBER, SYMBOL, NAME, and END.
- **Comments Handling**: `skip line()` function to ignore line-remaining characters.

## Running Blip
- Implement a `run()` function to read and execute Blip programs.
- **Testing**: Multiple small Blip programs can be read and tested during development.

## Design and Implementation Advice
- **Data Structures**: Used binary search trees or maps for symbol tables.
- **Parse Trees**: Optional but beneficial for representing the structure of Blip programs.
- **Recursion**: Essential for parsing and executing functions.
