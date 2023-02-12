+++
title = "Erg Programming Language"
sort_by = "weight"
+++

# Features

## __Robustness__

  Erg has a strong type system and comfortable compiler support. For example, it has dependent types and refinement types. These types strongly encode pre-conditions, invariant conditions, etc. into the code.

## __Simplicity & Consistency__

  Erg consists of a very simple and consistent syntax, which can significantly reduce the amount of code compared to other languages. However, its functionality is not inferior to them.
  Since the type inference system is powerful, you can code like a dynamically typed language.

## __Readability__

  In addition to the readability of the syntax itself, Erg defines a rich set of methods and functions by default to improve code readability.

## __Multi Paradigm__
  Functional & Object-Oriented

## __Maintainability__
  Erg requires some kinds of markers to be placed on code that causes side effects or changes internal state, which can localize the complexity of code. This will greatly improve the maintainability of your code.

## __Programmer Friendly__

  Erg is committed to providing error messages that are easy to read and various development tools. Erg also provide multilingual support for error messages, etc.

## __Interoperability with Python__

  Erg code can be compiled into Python bytecode. This means you have zero-cost access to your Python assets with Erg.

## __Multiple Backends__
  - CPython
  - __WIP__ Dyne (Python compatible bytecode interpreter, optimized to Erg's specifications, static types and the ownership system etc.)
  - __WIP__ LLVM (The compiler is called Gal, also optimized to Erg's specifications)