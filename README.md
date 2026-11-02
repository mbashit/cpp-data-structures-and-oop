# C++ Data Structures & OOP

![C++17](https://img.shields.io/badge/C%2B%2B-17-00599C?logo=cplusplus) ![CMake](https://img.shields.io/badge/build-CMake-064F8C?logo=cmake)

Classic data structures implemented from scratch with raw pointers, plus object-oriented programming labs (inheritance, operator overloading, abstract classes, templates). Written for university Algorithms & Data Structures and OOP courses.

## Projects

| Folder | Topic | Highlights |
|---|---|---|
| [`linked-list`](linked-list) | **Singly Linked List** | Pointer-based singly linked list split into header/implementation: insert at head / after node, delete, print, count occurrences of the maximum. |
| [`stack-bracket-matcher`](stack-bracket-matcher) | **Stack: Bracket Matcher** | Hand-written linked stack used to match `(` `)` pairs in an expression and print their positions sorted. |
| [`binary-tree`](binary-tree) | **Binary Tree Traversals** | Binary search tree: insert, delete, in/pre/post-order traversals written to files, and detection of nodes whose subtrees differ in height. |
| [`self-organizing-list`](self-organizing-list) | **Self-Organizing Doubly Linked List** | Doubly linked list class template with a nested iterator, insert/delete by iterator and move-to-front self-organisation. |
| [`operator-overloading-pair`](operator-overloading-pair) | **Operator Overloading & Inheritance** | `Pair` value type with arithmetic methods and overloaded operators, extended by a `Complex` number class. |
| [`polymorphism-money`](polymorphism-money) | **Polymorphism via Abstract Base Class** | Pure-virtual `Pair` interface implemented by `Money` (rubles/kopecks) and `Complex`, used through base-class pointers. |
| [`student-records`](student-records) | **Student Records (structs & enums)** | Structs and enums modelling students and exam results, persisted to binary (`.dat`) and text files. |

## Build & run

```bash
cmake -S . -B build
cmake --build build
./build/binary-tree
```

Each folder builds to an executable named after the folder. Input files (e.g. `binary-tree/*.txt`) are read from the working directory.

## Concepts demonstrated

- Manual memory management: `new` / `delete`, destructors, avoiding leaks
- Linked lists (singly & doubly), stacks, binary search trees
- Recursion for tree traversal and destruction
- Class templates and nested iterator classes
- Inheritance, virtual functions, abstract interfaces, operator overloading
- File I/O with `fstream` (text and binary)

## License

[MIT](LICENSE)
