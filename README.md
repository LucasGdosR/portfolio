# Portfolio
This repository points to my main repositories sorted by category.

## Compilers (OCaml)
- [Snake languages](https://github.com/LucasGdosR/snake-languages/tree/main) - an incremental compiler approach, building several compilers for increasingly rich LISP languages. Encompasses all projects from Joe Politz's [UCSD 131 compilers course](https://github.com/ucsd-cse131-f19/ucsd-cse131-f19.github.io/tree/master) (in progress)

## Systems (Mostly C)
- [Parallel zip](https://github.com/LucasGdosR/ostep-projects/tree/main/concurrency-pzip) - a multithreaded command-line program written in C that compresses files using run length encoding. One of the projects from [OS:TEP](https://pages.cs.wisc.edu/~remzi/Classes/537/Spring2018/Projects/p3.html) course.
- [Shell](https://github.com/LucasGdosR/ostep-projects/tree/main/processes-shell) - a Unix shell that implements some built in commands, output redirection, and executes binary files. One of the projects from [OS:TEP](https://pages.cs.wisc.edu/~remzi/Classes/537/Spring2018/Projects/p2a.html) course and one of the labs from [CS:APP3e](https://csapp.cs.cmu.edu/3e/labs.html).
- [Custom malloc](https://github.com/LucasGdosR/malloc-lab) - four different implementations of malloc, free and realloc, using different policies and free-list data structures. One of the labs from [CS:APP3e](https://csapp.cs.cmu.edu/3e/labs.html).
- [Cache simulator](https://github.com/LucasGdosR/cache-lab) - a simulator of processor's cache implementing LRU. One of the labs from [CS:APP3e](https://csapp.cs.cmu.edu/3e/labs.html).
- xv6 lottery scheduller - I've implemented a new scheduler policy for the xv6 kernel. I don't have it saved to a repo. One of the projects from [OS:TEP](https://pages.cs.wisc.edu/~remzi/Classes/537/Spring2018/Projects/p2b.html).
- [Assembler](https://github.com/LucasGdosR/nand2tetris/tree/main/assembler) - an assembler written in Java to convert symbolic assembly to machine code. Capstone of the first part of [Nand2Tetris](https://www.nand2tetris.org/) course.

## APIs (Java/Spring)
- [Lab Medical BD](https://github.com/LucasGdosR/DiP-M2-projeto-2) - a CRUD API using Spring. It's meant to complement the _Lab Medical_ frontend project.

## Unit Tests (Java/Spring)
- [Book API](https://github.com/LucasGdosR/BE-JV-011-TESTES-AUTOMATIZADOS) - a CRUD API using Spring centered around books. The main purpose of the project was to work on unit tests and integration tests using JUnit5.
- [Flight Ticket API](https://github.com/LucasGdosR/DiP-M3-projeto-1) - an API using Spring centered around a flight. The main purpose was to work on unit tests.

## Frontend (JS and Angular/TS)
- [DevInKnowledge](https://github.com/LucasGdosR/DiP-M1-projeto-1) - a CRUD using Vanilla HTML/CSS/JS and the browser's local storage for persistence. Does not use any framework.
- [Lab Medical](https://github.com/LucasGdosR/DiP-M-1-projeto-2) - a CRUD using Angular. There's a [github pages](https://lucasgdosr.github.io/DiP-M-1-projeto-2/) page.
- [Product Stock and Supplier CRUD](https://github.com/LucasGdosR/projeto-integrador-2023-1) - an MVP developed for stock control for a local business using Angular. Made for schoolwork only. There's a [github pages](https://lucasgdosr.github.io/projeto-integrador-2023-1/) page.

## Design Patterns (Java)
- [LabMedicine](https://github.com/LucasGdosR/DiP-M2-projeto-1) - a CRUD using pure Java. I implemented the _composite_ design pattern for the menu system.
- [Car tests](https://github.com/LucasGdosR/santander-coders-web-full-stack/tree/testes-automatizados-1/testes_automatizados_carros) - an exercise. I implemented all the rules in the Main.java file using the _state_ design pattern.

## Algorithms (Java / Python)
- [Binary Heaps](https://github.com/ppenna/playground/tree/main/data-structures/binary-heap/java) - some implementations of binary heaps in Java, including a "median heap", that always returns the median.
  - [A*](https://github.com/LucasGdosR/DSA-Exercises/tree/main/heaps/eight_puzzle) - A* implementation to solve the 8-puzzle game optimally.
- [BST](https://github.com/ppenna/playground/tree/main/data-structures/binary-search-tree/java) - a BST that can perform all kinds of operations based on _compare_ routines.
  - [IsBST](https://github.com/LucasGdosR/DSA-Exercises/tree/main/binary_trees/is_bst) - an algorithm to check if a tree is a binary search tree.
  - [2D Tree](https://github.com/LucasGdosR/DSA-Exercises/tree/main/binary_trees/kd_trees) - an efficient data structure to find all points inside a given rectangle, or to find the nearest point given another point.
- [CS50AI](https://github.com/LucasGdosR/DSA-Exercises/tree/main/CS50AI) (Python) - most projects from CS50AI.
- [Graphs](https://github.com/LucasGdosR/DSA-Exercises/tree/main/graphs) - many implementations. Includes undirected, directed, and weighted graphs, BFS, recursive DFS, and Kruskal's MST.
  - [Seam Carver](https://github.com/LucasGdosR/DSA-Exercises/blob/main/graphs/seam/SeamCarver.java) - an image editing application that computes the shortest path in an acyclic digraph using the pixels' energy as the edge's weight.
  - [Baseball Elimination](https://github.com/LucasGdosR/DSA-Exercises/tree/main/graphs/baseball) - an application that checks which baseball teams have been eliminated by computing the maxflow of a graph (maxflow < capacity of all edges leaving source -> eliminated), and finds which teams are responsible for the elimination by computing a mincut.
- [Sorting](https://github.com/LucasGdosR/DSA-Exercises/tree/main/sorting) - some sorting interview questions and implementations. Includes a [quicksort](https://github.com/ppenna/playground/tree/main/sorting/quicksort/java) implementation that's better suited for dealing with many duplicate keys in the array.
- [Stacks & Queues](https://github.com/LucasGdosR/DSA-Exercises/tree/main/stacks_queues) - a Deque implementation, a Stack implementation, a Queue implementation that uses 2 Stacks under the hood (not for production), and a Randomized Queue.
- [Tries](https://github.com/LucasGdosR/DSA-Exercises/tree/main/boggle) - an application to find all possible words in a Boggle board. It uses a Trie implemented from scratch holding words from a dictionary, and Depth First Search to find all valid words, with a Set holding the words found, to prevent duplicates.
- [Union Find](https://github.com/LucasGdosR/DSA-Exercises/tree/main/union_find) - some interesting interview questions answered, and a Monte Carlo simulation of a percolation problem.

## Misc
- [CS50 Final Project](https://github.com/LucasGdosR/CS50-Final-Project) (Python/Flask) - my first web application. It's filled with bad practices, but also has some linear programming using python's scipy, as well as frontend/backend integration using flask.
