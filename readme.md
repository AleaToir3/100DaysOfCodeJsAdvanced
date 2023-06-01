# Days 1 

Un peu plus de comprehention sur Js et son moteur V8 
Qui a cree ce moteur ?
    - Brendan Eich  a cree le 1er moteur Js qui etait spidermonkey
il existe une multitude de Moteur pour Js : (Engine Js )[https://en.wikipedia.org/wiki/List_of_ECMAScript_engines]
comment un fichier peut etre lue par un orditeur ? tout simplement avec une sorte de traducteur que on appele Engine
    - Chrome use V8 and V8 is wrinted with C++
    - in 2008 Chrome integer V8 with new methode to compile(JIT)... 

## What happen when we give a Js file to ur Engine 
    frist of all it making a Lexicale Analysis for break the code like that it can identify their meaning.
    this abstrat syntax are like a tree and it call AST we can have demo with : https://astexplorer.net/
    and they compile for get it out for ur CPU

    --------------------
# Days 1 

A bit more understanding about JavaScript and its V8 engine.
Who created this engine?
Brendan Eich created the first JavaScript engine called SpiderMonkey.
There are multiple engines for JavaScript. You can find a list of JavaScript engines here.[https://en.wikipedia.org/wiki/List_of_ECMAScript_engines]

How does a computer read a file? It uses a type of translator called an engine.
Chrome uses V8, which is written in C++.
In 2008, Chrome integrated V8 with a new method of compilation called JIT (Just-In-Time).


## What happens when we give a JavaScript file to your engine?
First of all, it performs Lexical Analysis to break down the code and identify its meaning. This abstract syntax is represented as a tree structure called an AST (Abstract Syntax Tree). You can explore an AST using this demo.[https://en.wikipedia.org/wiki/List_of_ECMAScript_engines]
Then, the code is compiled and executed by the engine to be processed by your CPU. 