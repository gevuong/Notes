# Learn and Understand NodeJS

## V8: The Javascript Engine
* The heart of NodeJS lies within the V8 JavaScript Engine

### Processors
* Microprocessors accepts instructions in particular language it understands, and carries them out. Microprocessors will likely speak one of these different machine languages such as: IA-32, x86-64, ARM, MIPS.

### Machine Code (aka Machine Language)
* Programming languages spoken by computer processors. Every program you run on your computer has been converted (or compiled) into machine code that your computer processor speaks.

* All code eventually becomes machine code.

* We've gone further and further abstracted away from lower-level code, and more into higher-level languages.

* Levels of Abstraction: Machine Language -> Assembly Language -> C/C++ -> Javascript (very high level, don't deal with where memory is and what it's doing, we have an engine that takes care of that for you)

## IMPORTANT: Node itself is written in C++. It's a C++ program because V8, which converts Javascript to machine code, is written in C++. V8 sits at the core of NodeJS.



### What is a Javascript Engine?
* A program that converts JS code into something the computer processor can understand. And it should follow the ECMAScript standard on how the language should work and what features it should have. There are many JS engines out there.

* V8 is Google's open-source JS engine, and was originally built to be used inside Chrome's browser.


### Adding Features to JS
* C++ has more features than Javascript as a programming language. JS was designed to be in the browser, not dealing with lower level operations like connecting to DB or dealing with files or folders in hard drive.

*
