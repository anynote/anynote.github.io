---
title:  "Functional Programming (FP)"
tags: fp functional programming
---
Working with immutable and pure function

## Definition

Style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing — state and mutable data

## What make a function `pure`

* Return the same result if given the same arguments (aka `deterministic`)

* Does not cause any observable side effects
it doesn't change/update any value

* _mutability is discouraged in functional programming_

## `Impure` function
* Use value from global object that not passed as a parameter
* Reading external files - the file's contents can change
* Any function that relies on a random number generator


## Pure functions benefit
code is easier to test: no need to mock the context

## Immutability
* Unchanging over time or unable to be changed.

* When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.

* The result of a function will be used as an input for the next function, without modifying the original input string.

## Referential transparency

`pure functions + immutable data = referential transparency`

# References
- [FreeCodeCamp - An introduction to the basic principles of Functional Programming](https://medium.freecodecamp.org/an-introduction-to-the-basic-principles-of-functional-programming-a2c2a15c84)
