# Awesome Intermediate Algorithms Repositories

The intermediate algorithms level builds on the fundamentals by exploring more challenging topics such as graph algorithms, combinatorial optimisation and network flow.  To help learners grow beyond the basics, this guide lists repositories that demonstrate intermediate‑level techniques across multiple programming paradigms.  Each topic contains repositories drawn from different language families (e.g., systems, object‑oriented, functional, concurrent and scripting languages).  As before, the summaries below cite the projects’ README files for context and focus on educational value over raw performance.

## General & intermediate‑level algorithms

| Repository | Primary language | Notes |
|---|---|---|
| TheAlgorithms/Ruby | Ruby | implementations of algorithms for educational purposes【924092462506359†L12-L15】 |
| TheAlgorithms/Haskell | Haskell | purely functional implementations of algorithms for learning【955580745195961†L3-L9】 |
| TheAlgorithms/C‑Sharp | C# | object‑oriented library of algorithms and data structures【562809867874612†L48-L52】 |

The **TheAlgorithms/Ruby** repository implements a wide range of algorithms in Ruby.  Its README notes that all algorithms are implemented for education and may be less efficient than Ruby’s standard library【924092462506359†L12-L15】.  Ruby’s expressive syntax and metaprogramming features make it an interesting modern systems language for learning algorithms.

**TheAlgorithms/Haskell** provides implementations in a purely functional language.  The repository states that all algorithms are implemented in Haskell for educational purposes and may be less efficient than standard library implementations【955580745195961†L3-L9】.  Haskell introduces lazy evaluation and strong type inference, giving learners a different paradigm for tackling algorithms.

**TheAlgorithms/C‑Sharp** (part of the TheAlgorithms project) offers C# implementations of classic algorithms and data structures.  Being a classic object‑oriented language, C# introduces learners to algorithms in a structured, strongly typed environment【562809867874612†L48-L52】.

## Graph algorithms & network flow

| Repository | Primary language | Notes |
|---|---|---|
| NetworkX | Python | library for creating and analysing complex networks【334237593037182†L30-L32】 |
| JGraphT | Java | graph‑theory objects and algorithms【821785669852255†L36-L38】 |
| igraph | C | efficient network analysis library【960315753944624†L13-L15】 |

The **NetworkX** package (Python) offers a rich collection of graph algorithms, including shortest paths, flows and connectivity.  Its README describes it as a library for creating, manipulating and studying complex networks【334237593037182†L30-L32】.

**JGraphT** is a Java library providing graph‑theory objects and algorithms.  According to its documentation, it requires JDK 11 or later and includes algorithms for shortest paths, maximum flows and matchings【821785669852255†L36-L38】.

**igraph** is written in C and focuses on efficiency and portability.  It provides functions for shortest‑path computations, clustering and other network analytics【960315753944624†L13-L15】.  The library also has bindings for R and Python, making it useful across languages.

## Optimisation & approximation

| Repository | Primary language | Notes |
|---|---|---|
| OR‑Tools | C++ (with wrappers) | suite of solvers for combinatorial optimisation【485867680653658†L36-L50】 |
| OptaPlanner | Java | AI constraint solver for planning problems【80114466440239†L47-L50】 |
| OptaPy | Python | Python bindings for OptaPlanner【966883765211098†L22-L27】 |

**OR‑Tools** is Google’s optimisation toolkit that includes linear programming, mixed integer programming and constraint programming solvers.  Its README emphasises its ability to tackle combinatorial optimisation problems such as bin packing, vehicle routing and network flow【485867680653658†L36-L50】.

**OptaPlanner** provides a Java API for constraint satisfaction and planning problems.  It helps developers implement vehicle routing, employee rostering and similar problems【80114466440239†L47-L50】.

**OptaPy** wraps the OptaPlanner engine in Python, allowing Python developers to model and solve optimisation problems using the same underlying solver【966883765211098†L22-L27】.

## Randomised and functional approaches

| Repository | Primary language | Notes |
|---|---|---|
| TheAlgorithms/Go | Go | implementations in a systems language with built‑in concurrency【115586576422125†L18-L22】 |
| Arcane Algorithm Archive | Multi‑language | community project implementing algorithms in many languages【241678888670394†L2-L6】 |
| keon/algorithms | Python | clean implementations for learning【114983257491694†L13-L17】 |

**TheAlgorithms/Go** repository showcases algorithms in Go, a modern language that supports concurrency by design.  Its README notes that implementations are for educational use and may not match standard library efficiency【115586576422125†L18-L22】.

The **Arcane Algorithm Archive** is a collaborative project implementing algorithms in many languages (Rust, C++, JavaScript and more).  Its goal is to build a multi‑paradigm, multi‑language guide to algorithms【241678888670394†L2-L6】.

**keon/algorithms** provides minimal and clean Python implementations of data structures and algorithms.  This repository is ideal for practising algorithmic ideas in a straightforward scripting language【114983257491694†L13-L17】.

## Advanced sorting & searching

| Repository | Primary language | Notes |
|---|---|---|
| Sorting‑Algorithms | C++ | implementations of 12 classic sorting algorithms【879379053910588†L3-L14】 |
| Python_Sorting_Algorithms | Python | demonstrations of sorting with explanations【10392558027209†L2-L6】 |
| js‑sorting | JavaScript | library of sorting algorithms with complexity details【373179690977657†L5-L8】 |

Intermediate learners benefit from revisiting sorting algorithms using more complex data structures and optimised implementations.  The **Sorting‑Algorithms** project in C++ implements twelve classic sorting algorithms and annotates each with time and space complexity【879379053910588†L3-L14】.  **Python_Sorting_Algorithms** emphasises how algorithm design affects efficiency【10392558027209†L2-L6】, while **js‑sorting** collects sorting methods for event‑driven JavaScript environments【373179690977657†L5-L8】.

---

These intermediate resources bridge the gap between beginner and advanced algorithm work.  They introduce additional programming paradigms (functional, object‑oriented, systems, concurrent) and provide concrete code examples for graph algorithms, optimisation and more.  Exploring a variety of languages and paradigms helps build a flexible understanding of algorithmic problem solving.