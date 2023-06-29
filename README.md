# Compiler
A simple compiler written in C++. The compiler is designed to parse and interpret a custom programming language with a syntax similar to C.

## Structure

- ``` demo.cc ```: This file contains the main driver code for the compiler. It includes the implementation of the parsing functions for the various constructs of the language such as variables, expressions, statements, and control structures. It also includes the implementation of the interpreter that executes the parsed code.

- ``` inputbuf.cc and inputbuf.h ```: These files implement a simple input buffer for reading the source code.

- ``` lexer.cc and lexer.h ```: These files implement a lexical analyzer (lexer) that tokenizes the source code.

## Building and Running the Compiler

To build the compiler, you need a C++ compiler that supports the C++11 standard. You can build the compiler using the following command:

```
g++ -std=c++11 -o compiler demo.cc inputbuf.cc lexer.cc
```
This will produce an executable named compiler. You can run it on a source code file like this:

```
./compiler source.txt
```
Replace ``` source.txt ``` with the path to the file containing the source code you want to compile.

## Language Syntax

The language supported by this compiler has a syntax similar to C. It supports the following constructs:

- Variable declarations
- Assignment statements
- Arithmetic expressions
- Control structures (if, while, switch, for)
- Input and output operations
  
For more details on the syntax of the language, please refer to the parsing functions in the demo.cc file.

## Contributions

Contributions to this project are welcome. If you find a bug or want to add a new feature, please open an issue or submit a pull request.
