+++
title = "Erg Programming Language"
sort_by = "weight"
+++

# Features

- __Robustness__

  Erg has a strong type system. For example, it has dependent types and refinement types. These types strongly encode pre-conditions, invariant conditions, etc. into the code.

- __Readability__

  In addition to the readability of the syntax itself, Erg defines a rich set of methods and functions by default to improve code readability.

- __Programmer Friendly__

  Erg is committed to providing error messages that are easy to read. Erg also provide multilingual support for error messages, etc.

- __Multi Paradigm__
  - Functional & Object-Oriented

- __Incrementally improve your Python codebase__

  Erg code can be compiled into Python bytecode. This means you have zero-cost access to your Python assets with Erg. It is also easy to type and call Python APIs, like TypeScript.

- __Multiple Backends__
  - CPython
  - __WIP__ Dyne (Python compatible bytecode interpreter, optimized to Erg's specifications, static types and the ownership system etc.)
  - __WIP__ LLVM (The compiler is called Gal, also optimized to Erg's specifications same as Dyne)