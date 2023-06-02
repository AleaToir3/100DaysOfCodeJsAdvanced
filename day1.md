# Day 1 

A bit more understanding about JavaScript and its V8 engine.
Who created this engine?
Brendan Eich created the first JavaScript engine called SpiderMonkey.
There are multiple engines for JavaScript. You can find a list of JavaScript engines [here](https://en.wikipedia.org/wiki/List_of_ECMAScript_engines)

How does a computer read a file? It uses a type of translator called an engine.
Chrome uses V8, which is written in C++.
In 2008, Chrome integrated V8 with a new method of compilation called JIT (Just-In-Time).


## What happens when we give a JavaScript file to your engine?
First of all, it performs Lexical Analysis to break down the code and identify its meaning. This abstract syntax is represented as a tree structure called an AST (Abstract Syntax Tree). You can explore an AST using [this demo.](https://en.wikipedia.org/wiki/List_of_ECMAScript_engines)
Then, the code is compiled and executed by the engine to be processed by your CPU. 
