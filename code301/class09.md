# Functional Programming in JavaScript


Functional Programming is a programming paradigm where you mostly construct and structure your code using functions. ... It presents an answer to its elegant function in a straightforward manner. It's also worth noting that JavaScript is a multi-paradigm programming language and Functional Programming is one of them.

**Pure Functions**

A pure function is a function which: Given the same input, will always return the same output. Produces no side effects,Pure functions are the atomic building blocks in functional programming. They are adored for their simplicity and testability.
![image](https://cdn-media-1.freecodecamp.org/images/0*a_yub2gTwY-1eK8j.png)

![image](https://image.slidesharecdn.com/purefunctions-161018130223/95/pure-functions-using-javascript-4-638.jpg?cb=1476796010.png)


Pure functions are much easier to read and reason about. All relevant inputs and dependencies are provided as parameters, so no effects are observed that alter variables outside of the set of inputs. This means that we can quickly understand a function and its dependencies, just by reading the function's declaration.

## Immutability in JavaScript

Immutability is a core principle in functional programming, and has lots to offer to object-oriented programs as well. In this article, I will show what exactly immutability is all about, how to use this concept in JavaScript, and why it’s useful.


The text-book definition of mutability is liable or subject to change or alteration. In programming, we use the word to mean objects whose state is allowed to change over time. An immutable value is the exact opposite – after it has been created, it can never change.

## What Is Referential Transparency?

In functional programming, referential transparency is generally defined as the fact that an expression, in a program, may be replaced by its value (or anything having the same value) without changing the result of the program. This implies that methods should always return the same value for a given argument, without having any other effect. This functional programming concept also applies to imperative programming, though, and can help you make your code clearer.
The expression referential transparency is used in various domains, such as mathematics, logic, linguistics, philosophy and programming. It has quite different meanings in each of these domain. Here, we will deal only with computer programs, although we will show analogy with maths (simple maths, don’t worry). Note, however, that computer scientists do not agree on the meaning of referential transparency in programming. What we will look at is referential transparency as it is used by functional programmers.