# Regular Expression to Finite Automaton Conversion

This project is part of a course on "Languages and Compilers" and focuses on the conversion of regular expressions (RE) into deterministic finite automata (DFA). The project consists of two main parts:

1. **Conversion from Regular Expression to Non-Deterministic Finite Automaton (NFAs):** This part of the project involves reading an input file that contains the representation of a regular expression in the form of an Abstract Syntax Tree (AST). The AST is parsed and converted into a Non-Deterministic Finite Automaton (NFA) using the Subset Construction algorithm. The resulting NFA represents the language defined by the input regular expression.

2. **Deterministic Finite Automaton (DFA) Construction:** The NFA generated in the first part is further processed using the Subset Construction algorithm to create an equivalent Deterministic Finite Automaton (DFA). The DFA is represented as a set of states and transition functions and is ready for use in lexical analysis and pattern matching.

## Project Structure

- `postorder.cpp`: The C++ code provided for parsing and converting regular expressions into NFAs.
- `input.txt`: An example input file containing the representation of a regular expression in AST format.

## Usage

You can use the provided code as a foundation for your project. Modify the code as needed to suit your requirements, and adapt it to handle different regular expressions and input files.
Must use up to date g++ compiler (if ran on mac make sure you're not using clang)
