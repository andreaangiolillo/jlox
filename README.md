# jlox

A tree-walk interpreter for the **Lox programming language**, written in Java as part of working through [Crafting Interpreters](https://craftinginterpreters.com/) by Robert Nystrom.

## About

This repository contains my implementation of **jlox**, the Java interpreter introduced in *Crafting Interpreters*.

The goal of this project is to gain a deeper understanding of how programming languages work, from lexical analysis and parsing to evaluating expressions and executing programs.

The project uses **Bazel** as its build system.

## Getting Started

### Prerequisites

- Java JDK
- Bazel (or Bazelisk)

### Build

Clone the repository and build the interpreter:

```bash
bazel build //:jlox
```

### Run

Launch the interpreter:

```bash
bazel run //:jlox
```

*The commands above assume the Bazel target is named `jlox` and is defined in the repository root.*

## Progress

This is a work in progress. The interpreter is being implemented incrementally as I work through the book.

## Acknowledgements

This project follows [Crafting Interpreters](https://craftinginterpreters.com/) by [Robert Nystrom](https://github.com/munificent).

The Lox language and the original interpreter design are introduced in the book.
