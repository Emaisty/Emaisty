# Hi, I'm Max

Student of Master studies at Aarhus Uni. I'm really into *theoretical informatics* and like to explore things in it.
I'm particularly passionate about **Programming Language Theory**. 

Right now, I'm studying verification techniques and looking forward to putting my knowledge into practice.

## My PLT projects

### [IRIS on Arend](https://github.com/Emaisty/IRIS)

My master's thesis.
Separation logic framework, originally implemented for the [rocq](https://gitlab.mpi-sws.org/iris/iris/), rewritten for the [Arend theorem prover](https://arend-lang.github.io/).
Conservative port, preserving the interface and structure of proofs, created on the Homotopy type theory.

### [TinyGo Compiler](https://github.com/Emaisty/Compiler_for_TinyGO)

My bachelor's thesis.
It is a compiler for a simplified version of GoLang.
It preserves all original language features, except for STL(obviously), package manager, and concurrent programming (for future improvements).

In future versions, I would like to extend it with a verification tool, to check for liveness properties and detect data-race.

### [Sharded counter on IRIS](https://github.com/Emaisty/IRIS-Array-based-Counter)

Small proof written on the IRIS.
The counter is split into shards, where each thread can safely increase its own shard of memory without needing to lock. 
Read operation is a combination sum of all shards.
Proof shows that we can treat the incr and read as logically atomic operations.
Also, shown a contextual equivalence between the sharded, linear, and sequential counters.

### [Parser for Pascal-like lang](https://github.com/Emaisty/Mila_parser)

Front-end parser for the Pascal-like language.
Transforms the source code into IR with the use of LLVM.
Supports nested dependencies and recursions.

## My other projects

### [Lisp evaluator](https://github.com/Emaisty/Lisp_evaluator)

Simple Lisp parser and evaluator. 
Takes a program written in a Lisp language and returns the result.
Works only with constants.

Parser written in C++. Consists of a lexer, parser, and AST. 
AST evaluates the program by itself.

### [Alias](https://github.com/Emaisty/Alias)

GUI-based game, written in Go with the use of [qt](https://github.com/therecipe/qt).

### [Long number library](https://github.com/Emaisty/Longnum)

Library for C++ with support of long numbers and long arithmetic.
Numbers are represented as an array of booleans.

### [Terminal-based Heartstone game](https://github.com/Emaisty/CardGame)

Simplified Hearthstone-like game with terminal-based graphics. 

