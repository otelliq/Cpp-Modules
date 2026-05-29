<div align="center">

# 42 C++ Modules

*From procedural instincts to object-oriented mastery.*

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Makefile](https://img.shields.io/badge/Makefile-000000?style=for-the-badge&logo=gnu&logoColor=white)
![42](https://img.shields.io/badge/42-000000?style=for-the-badge&logo=42&logoColor=white)

</div>

---

## About

This repository contains my solutions to the **42 Network C++ Modules (00–09)**.

The modules progressively introduce core concepts of **C++ (C++98)** — from the basics (classes, namespaces, I/O) to more advanced topics like inheritance, polymorphism, exceptions, casts, templates, and STL fundamentals.

> The goal is not only to complete the exercises, but to build a strong understanding of how C++ works and how to write clean, maintainable OOP code.

---

## Modules overview

| Module | Focus | Key topics |
|---|---|---|
| **cpp00** | Basics | namespaces, classes, member functions, `iostream` |
| **cpp01** | Memory & references | `new/delete`, references vs pointers, file streams |
| **cpp02** | Ad-hoc polymorphism | operator overloading, canonical form |
| **cpp03** | Inheritance | base/derived classes, constructor/destructor chain |
| **cpp04** | Polymorphism | virtual functions, abstract classes, interfaces |
| **cpp05** | Exceptions | `try/catch`, custom exceptions |
| **cpp06** | Casts | `static_cast`, `dynamic_cast`, conversions |
| **cpp07** | Templates | function & class templates |
| **cpp08** | STL intro | containers, iterators, basic algorithms |
| **cpp09** | Mixed advanced usage | combining concepts, algorithms practice |

---

## Repository structure

```text
Cpp-Modules/
├── cpp00/
├── cpp01/
├── cpp02/
├── cpp03/
├── cpp04/
├── cpp05/
├── cpp06/
├── cpp07/
├── cpp08/
├── cpp09/
└── README.md
```

Each module typically contains:

- exercise folders (`ex00`, `ex01`, ...)
- a `Makefile`
- subject-compliant `*.cpp` / `*.hpp` files

---

## Build & run

All exercises are designed for **C++98**.

```bash
# Example: compile an exercise
cd cppXX/exYY
make

# Run
./<program>
```

> The executable name depends on the exercise/Makefile.

---

## Notes / rules followed

- C++98 only (per 42 subject)
- no external libraries unless explicitly allowed
- Makefile required for each exercise
- focus on correctness, clean design, and avoiding leaks (where applicable)

---

## Author

<div align="center">

Built as part of the **42 Network** curriculum  
by **Othmane Elliq**

</div>
