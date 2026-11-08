# Formal Verification with Rocq (Coq)

**CMSC433 — Programming Language Technologies and Paradigms**  
**University of Maryland, College Park | Fall 2025 | Projects 5 & 6**

This repository provides a technical overview of a CMSC433 coursework project. The original implementation and assignment materials are not publicly distributed in accordance with course policies.

## Overview

This repository contains two related projects developed for CMSC433 at the University of Maryland, exploring **formal verification, functional programming, and mathematical proofs** using the **Rocq proof assistant (formerly Coq)**.

The projects focus on constructing mathematically rigorous proofs of program properties, working with recursive functions and data structures, and using automated proof-checking tools to verify correctness.

Project 5 introduces the fundamentals of theorem proving, while Project 6 expands on these concepts through polymorphism, advanced proof tactics, and propositional logic.

## Project 5 — Rocq Basics and Inductive Proofs

**Main Files:** `Basics.v`, `Induction.v`, `Lists.v`

This project introduces the foundations of formal reasoning and interactive theorem proving using Rocq.

### Key Concepts

- **Functional Programming:** Defining recursive functions, Boolean operations, and natural number arithmetic.
- **Inductive Data Types:** Working with natural numbers, lists, and other recursively defined structures.
- **Mathematical Induction:** Proving properties of recursive functions using structural induction.
- **List Operations:** Verifying properties of list concatenation, reversal, and length.
- **Logical Reasoning:** Expressing mathematical properties as theorems and constructing machine-checked proofs.
- **Partial Maps:** Exploring key-value mappings and proving properties of lookup and update operations.

### Learning Objectives

- Understand how mathematical proofs can establish program correctness.
- Apply induction to verify recursive functions and data structures.
- Develop proofs using Rocq tactics such as `intros`, `simpl`, `rewrite`, and `induction`.
- Translate mathematical statements into formal, machine-checkable theorems.

## Project 6 — Advanced Proof Tactics and Logic

**Main Files:** `Poly.v`, `Tactics.v`, `Logic.v`

Building on Project 5, this project explores more advanced concepts in functional programming and formal logic.

### Key Concepts

- **Polymorphism:** Defining and verifying generic functions that operate on multiple data types.
- **Higher-Order Functions:** Working with functions such as `map`, `filter`, and `fold`.
- **Advanced Proof Tactics:** Using techniques including case analysis, generalization, rewriting, and induction.
- **Propositional Logic:** Constructing proofs involving conjunction, disjunction, implication, and negation.
- **Logical Equivalence:** Proving relationships between propositions, including distributive properties and De Morgan's laws.
- **Formal Correctness:** Demonstrating that functions and mathematical statements satisfy specified properties.

### Learning Objectives

- Develop a deeper understanding of interactive theorem proving.
- Construct proofs involving polymorphic and higher-order functions.
- Apply advanced proof tactics to simplify complex verification problems.
- Express and verify logical relationships using formal mathematical reasoning.

## Technologies and Tools

| Technology | Purpose |
|---|---|
| Rocq / Coq | Interactive theorem proving and formal verification |
| Gallina | Functional programming and theorem specification |
| Rocq Proof Tactics | Constructing and checking mathematical proofs |
| Structural Induction | Verifying recursive functions and data structures |
| Propositional Logic | Reasoning about logical expressions and equivalence |
| Make | Compiling and checking proof files |

## Repository Structure

```text
rocq-formal-verification/
│
├── README.md
│
├── project-5/
│   ├── Basics.v
│   ├── Induction.v
│   ├── Lists.v
│   ├── BasicsTest.v
│   ├── InductionTest.v
│   ├── ListsTest.v
│   ├── Makefile
│   └── _CoqProject
│
└── project-6/
    ├── Basics.v
    ├── Induction.v
    ├── Lists.v
    ├── Poly.v
    ├── Tactics.v
    ├── Logic.v
    ├── PolyTest.v
    ├── TacticsTest.v
    ├── LogicTest.v
    ├── Makefile
    └── _CoqProject
```

Project 6 includes prerequisite material from Project 5. The projects are organized into separate directories to preserve their respective dependencies and build configurations.

## Running the Projects

### Prerequisites

- A compatible installation of Rocq/Coq
- Make build utility

### Project 5

Navigate to the Project 5 directory:

```bash
cd project-5
make
```

### Project 6

Navigate to the Project 6 directory:

```bash
cd project-6
make
```

The included Makefiles compile the Rocq source files and check their formal definitions and proofs.

**Note:** Successful compilation depends on the installed Rocq/Coq version and the completeness of the included proofs. The complete test suites have not been independently verified for this repository.

## Skills Demonstrated

Through these projects, I gained practical experience with:

- **Formal Verification:** Using mathematical proofs to reason about software correctness.
- **Functional Programming:** Defining recursive, polymorphic, and higher-order functions.
- **Theorem Proving:** Constructing machine-checkable proofs using Rocq.
- **Mathematical Logic:** Applying induction, propositional logic, and logical equivalence.
- **Proof Development:** Using interactive proof tactics to solve complex verification problems.
- **Program Correctness:** Understanding how formal methods can establish properties beyond conventional software testing.

## Academic Context

These projects were completed as part of **CMSC433: Programming Language Technologies and Paradigms** at the **University of Maryland, College Park**, during Fall 2025.

The assignments build on course-provided materials and concepts from *Software Foundations: Logical Foundations*. Starter code, exercises, and test files were provided as part of the course.

The work demonstrates experience with formal methods, functional programming, and theorem proving.

**Academic Integrity:** The supplied course materials request that assignment solutions not be distributed publicly. Any repository containing completed solutions should remain private unless public sharing is explicitly permitted.
