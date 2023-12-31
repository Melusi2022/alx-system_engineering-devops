0x04. Loops, conditions and parsing

Parsing is performed at the syntax analysis phase where a stream of tokens is taken as input from the lexical analyzer and the parser produces the parser tree for the tokens while checking the stream of tokens against the syntax errors.

Role of Parser
In the syntax analysis phase, a compiler verifies whether or not the tokens generated by the lexical analyzer are grouped according to the syntactic rules of the language. This is done by a parser. The parser obtains a string of tokens from the lexical analyzer and verifies that the string can be the grammar for the source language. It detects and reports any syntax errors and produces a parse tree from which intermediate code can be generated.

Parser
 

Types of Parsing
The parsing is divided into two types, which are as follows:

1. Top-down Parsing

2. Bottom-up Parsing

Top-Down Parsing
Top-down parsing attempts to build the parse tree from the root node to the leaf node. The top-down parser will start from the start symbol and proceed to the string. It follows the leftmost derivation. In leftmost derivation, the leftmost non-terminal in each sentential is always chosen. 

Recursive parsing or predictive parsing are other names for top-down parsing.
A parse tree is built for an input string using bottom-up parsing.
When parsing is done top-down, the input symbol is first transformed into the start symbol.
The top-down parsing is further categorized as follows:

1. With Backtracking: 

Brute Force Technique
2. Without Backtracking: 

Recursive Descent Parsing
Predictive Parsing or Non-Recursive Parsing or LL(1) Parsing or Table Driver Parsing
Bottom-up Parsing
Bottom-up parsing builds the parse tree from the leaf node to the root node. The bottom-up parsing will reduce the input string to the start symbol. It traces the rightmost derivation of the string in reverse. Bottom-up parsers are also known as shift-reduce parsers.

Shift-reduce parsing is another name for bottom-up parsing.
A parse tree is built for an input string using bottom-up parsing.
When parsing from the bottom up, the process begins with the input symbol and builds the parse tree up to the start symbol by reversing the rightmost string derivations.
