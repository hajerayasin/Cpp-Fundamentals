# Chapter 1 — Introduction to C++

## Topics Covered

- What is Programming
- What is C++
- History of C++
- Compiler
- Source Code
- Object Code
- Executable File
- Keywords
- Identifiers
- Basic Structure of a C++ Program
- Input and Output
- Comments

---

# What is Programming?

Programming is the process of writing instructions for a computer to perform specific tasks.

---

# What is C++?

C++ is a high-level programming language developed by Bjarne Stroustrup.  
It is used for system software, games, applications, and competitive programming.

---

# Basic Structure of a C++ Program

   cpp
#include <iostream>
using namespace std;

int main()
{
    cout << "Hello World";

    return 0;
}
```

---

# Explanation of Program

## #include <iostream>

Used for input and output operations.

## using namespace std;

Allows use of standard library names without writing std:: every time.

## int main()

Main function where program execution starts.

## cout

Used to display output on screen.

## return 0;

Indicates successful execution of program.

---

# Keywords

Keywords are reserved words in C++ that have special meanings.

Examples:

- int
- float
- return
- if
- else
- while

---

# Identifiers

Identifiers are names given to variables, functions, and arrays.

Example:

```cpp
int age;
```

Here, `age` is an identifier.

---

# Comments

Comments are notes written inside code for explanation.

## Single Line Comment

```cpp
// This is a comment
```

## Multi Line Comment

```cpp
/*
This is
multi line comment
*/
```

---

# Input and Output

## Output Statement

```cpp
cout << "Hello";
```

## Input Statement

```cpp
cin >> variableName;
```

---

# Important Notes

- C++ is case-sensitive.
- Every statement ends with semicolon `;`
- Program execution starts from `main()`
- Curly braces `{}` define a block of code.
