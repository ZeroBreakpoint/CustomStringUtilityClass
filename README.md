# Custom String Utility Class (C++)

This project implements a robust, reusable `String` class in C++ to simplify operations on C-style character arrays.  Built from scratch as part of an Academy of Interactive Entertainment (AIE) assessment, this system demonstrates object-oriented design, memory safety and operator overloading.

## Features

- `Length()` — Returns the number of characters (excluding null terminator)
- `CharacterAt(index)` — Returns character at a given index (safe-bounds access)
- `EqualTo(str)` — Checks string equality
- `Append(str)` / `Prepend(str)` — Concatenates strings at end or start
- `CStr()` — Accesses raw `const char*` for use with standard I/O
- `ToLower()` / `ToUpper()` — Converts characters to lower/upper case
- `Find(str)` / `Find(startIndex, str)` — Searches for substring
- `Replace(find, replace)` — Replaces all occurrences of a substring
- `ReadFromConsole()` / `WriteToConsole()` — Supports console interaction

## Operator Overloads

- `==`, `!=` — Equality/Inequality comparisons
- `=` — Assignment
- `[]` — Subscript access (non-const and const)
- `<` — Lexicographic comparison

## Sample Application

The `Assessment_1.cpp` file demonstrates the usage of the `String` class by:

- Creating and manipulating strings
- Outputting "Hello, World" using your custom class
- Applying each implemented function for demonstration and validation

## Getting Started

1. Clone this repository.
2. Open in Visual Studio or your preferred IDE.
3. Compile and run `Assessment_1.cpp`.
