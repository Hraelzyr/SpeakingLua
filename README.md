# SpeakingLua
###### A project to interpret a subset of Lua.  
Lua is dynamically typed and needs no explicit casts for type. Check the [Lua reference manual](https://www.lua.org/manual/) for details.  
The interfaces for our code and the meaning of each step can be found [here](https://ruslanspivak.com/lsbasi-part7/). The given is part 7, the bare minimum to get started.

##### How to Use
Run test_semantiff.py.
The code in code.txt is run and the variables are outputted at program end.

The given example is such that:
a=4000
a2=10
b2=3025
a3=22.0
a4=7.83
a5=2
b5=11
c5=20

The code file may be changed to check various files.
Further, the file interactive.py allows a text console.

## Lexer
#### Niraj and Abhinav
Input: A stream of characters i.e. string

Output: The next token(number/identifier/keyword/...)

## Parser
#### B Teja and Keshav
Input: A list of tokens one at a time, with a lookahead of 1 token.

Output: The AST(Abstract Syntax Tree)

## Semantic analyser
#### Arvind Srinivasan
Input: AST

Output: Execution


