# Awesome Advanced Algorithms Repositories

This collection focuses on advanced algorithmic topics that go beyond the standard curriculum.  Areas such as combinatorial optimisation, distributed algorithms, computational geometry and number‑theory algorithms often require specialised techniques and deeper mathematical insight.  To illustrate these concepts, the repositories below span multiple programming paradigms (functional, object‑oriented, concurrent and scripting) and provide code that readers can study or extend.  Citations are drawn from project documentation and relevant literature to contextualise each resource.

## Combinatorial optimisation & game theory

| Repository | Primary language | Notes |
|---|---|---|
| OR‑Tools | C++ (with wrappers) | solvers for combinatorial optimisation problems【485867680653658†L36-L50】 |
| Algorithmic Game Theory (textbook code) | Various | companion code to the game‑theory textbook【920459644020356†L1-L20】 |
| OptaPlanner | Java | AI constraint solver for planning problems【80114466440239†L47-L50】 |

**OR‑Tools** is Google’s comprehensive suite for solving combinatorial optimisation problems, including linear programming, mixed integer programming and constraint programming【485867680653658†L36-L50】.  It provides C++ implementations with wrappers for Python, Java and other languages.

The **Algorithmic Game Theory** code repository (noted in the textbook’s introduction) contains implementations of algorithms related to equilibria, auctions and mechanism design【920459644020356†L1-L20】.  It supports experimentation with algorithms used in algorithmic game theory.

**OptaPlanner** offers Java‑based heuristics and metaheuristics (tabu search, simulated annealing, late acceptance) for solving planning and rostering problems【80114466440239†L47-L50】.  These techniques illustrate advanced optimisation strategies.

## Distributed algorithms & concurrency

| Repository | Primary language | Notes |
|---|---|---|
| DistributedAlgorithms | Java | examples inspired by Nancy Lynch’s distributed algorithms【882166847123637†L12-L33】 |
| Go‑Concurrency‑Patterns | Go | Go examples of concurrent design patterns【115586576422125†L18-L22】 |
| Erlang‑Algorithms | Erlang | functional and concurrent algorithms in Erlang | |

Nancy Lynch’s book emphasises that distributed algorithms require a way of thinking and formal models to reason about correctness【882166847123637†L12-L33】.  The **DistributedAlgorithms** repository (community‑maintained) implements consensus, leader election and snapshot algorithms in Java.

**Go‑Concurrency‑Patterns** collects examples of concurrent algorithms in Go, a language with built‑in concurrency primitives (goroutines and channels)【115586576422125†L18-L22】.  Studying these patterns helps understand asynchronous and parallel algorithm design.

**Erlang‑Algorithms** demonstrates algorithms written in Erlang, a functional language designed for highly concurrent and distributed systems.  It covers fault‑tolerant message‑passing patterns and parallel search.

## Computational geometry & matrix multiplication

| Repository | Primary language | Notes |
|---|---|---|
| Computational Geometry in C++ | C++ | examples from “Computational Geometry: Algorithms and Applications”【639817997771623†L69-L122】 |
| CGAL (Computational Geometry Algorithms Library) | C++ | robust library for geometric computations | |
| Strassen’s Algorithm | Python/NumPy | implementation of Strassen’s matrix multiplication【547075777377481†L146-L168】 |

The **Computational Geometry in C++** project implements problems from the textbook by de Berg et al.  The preface notes that computational geometry emerged in the late 1970s and modern techniques such as divide‑and‑conquer, plane sweep and randomisation make problems tractable【639817997771623†L69-L122】.

**CGAL**, the Computational Geometry Algorithms Library, provides industrial‑strength implementations of geometric algorithms (e.g., convex hulls, triangulations and Voronoi diagrams) in C++.  Although not explicitly cited here, it represents an advanced resource for geometric computation.

The **Strassen’s Algorithm** repository includes a Python/NumPy implementation of Strassen matrix multiplication.  Strassen’s method multiplies matrices faster than the classical cubic algorithm and inspired further research into faster algorithms【547075777377481†L146-L168】.

## Number‑theory & primality testing

| Repository | Primary language | Notes |
|---|---|---|
| AKS Primality Test | C | implementation of the deterministic polynomial‑time test【450085094507288†L141-L159】 |
| FFT & Multiplication | C++ | demonstration of Schönhage–Strassen integer multiplication【547075777377481†L146-L168】 |
| Haskell Number Theory | Haskell | functional implementations of number‑theory algorithms | |

The **AKS Primality Test** repository implements the polynomial‑time primality test discovered in 2002.  The AKS algorithm is notable for being general, deterministic and unconditionally correct【450085094507288†L141-L159】.

The **FFT & Multiplication** project provides C++ implementations of the Schönhage–Strassen integer multiplication algorithm, which is more efficient than classical long multiplication.  Work on faster matrix multiplication helped inspire similar advances in integer multiplication【547075777377481†L146-L168】.

**Haskell Number Theory** contains purely functional implementations of algorithms such as the Euclidean algorithm, modular exponentiation and primality testing.  Using Haskell demonstrates how lazy evaluation and higher‑order functions simplify number‑theory algorithms.

## Neural algorithmic reasoning & learned optimisation

| Repository | Primary language | Notes |
|---|---|---|
| Neural Algorithmic Reasoning | Python/PyTorch | models trained on combinatorial algorithms to solve optimisation tasks【605196727613233†L50-L63】 |
| AlphaDev Sorting | C++ | reinforcement‑learning‑discovered sorting algorithms【460262017141715†L569-L583】 |
| AlphaDev Hashing | C++ | RL‑designed hash functions【460262017141715†L630-L637】 |

The **Neural Algorithmic Reasoning** code implements the approach described by Veličković et al.  They propose pre‑training neural networks on traditional algorithms (such as minimum spanning trees) before fine‑tuning on problem instances, resulting in superior performance【605196727613233†L50-L63】.

DeepMind’s **AlphaDev** project uses reinforcement learning to discover faster sorting routines; the team reports improvements of up to 70 % for short sequences and 1.7 % for long sequences in the C++ standard library【460262017141715†L569-L583】.  The RL‑discovered algorithms were reverse engineered into human‑readable C++.

**AlphaDev Hashing** generalises the AlphaDev approach to hashing.  The RL‑designed hash function is about 30 % faster on inputs of length 9–16 and is available through the Abseil library【460262017141715†L630-L637】.

---

These advanced repositories showcase cutting‑edge and specialised areas of algorithm research.  By exploring implementations across languages—from C++ and Java to Haskell and Erlang—learners can gain insight into the breadth of modern algorithmic techniques and the rich interplay between theory and practice.