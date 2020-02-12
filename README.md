Day-1
------------
javascript: scripting lang, OOP and functional, Interpretted, 
      loosely-typed: data-type decided based on assigned literal value.
                     var name = "abcd"
                     name = 22; name++; //VALID
- event-based, call-backs,
- single-threaded.
----------------------------
- in JS api registry of all callbacks.
- stack and eventqueue and eventloop concept in JS.
- JS runs on JS engine - V8
  other js engines: spidermonkey (firefox, adobe products)
  - Chakra and continnum (ms use it)
  - nashhorn
------------------------------
SCOPES in JS:
all js engines as of now supports only ECMAScript-5.
-In JS only function-scope and global-scope, there is no block-scope.
- HOISTING
- 'var' without 
BEST practice: 'use strict'
======================================
diff between function and Function
- meaning of ; in js....by default get added at the end of each line.
; semicolon insertion.
-token analyzer
Best practice: data.push instead of data[99]=100;
---------------------
a) object owned instance method approach is memory intensive, because even functions are copied in every instance.
better go for 'class owned' approach.
- JS by addy osmani, design patterns.
- Person.Prototype vs Person.Compare? 2nd is static method, 1st is instance method.

------------
java/C#: can't access object by address, because in heap objects keeps moving in GC 0,1,2...so no concept of address.
-----------
.bind() vs .call()
=======================
Functional programming:

== versus ===
===================================
- function returning function.
- closure:
- currying   adder(20)(4);   adder(22)(4)(5);
- Memoize()

=======================
ES6 = ES 2015
ES7 = ESNext

transpilers: Babel/Traucer

'let' - introduced for block-level scope.

` - backtick is kind of string.format with placeholder eveluated and for multiline.

array Deconstructing;

---------------

Generators with *:

SAGA framework using 'yields'.

==================================
Day 2:
---------
default: keyword - when used, while importing it, it doesn't need {}.
export default class abc
=================================================




