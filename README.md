# CKY Parser

This is a python3 CKY parser. It parses a grammar in Doty syntax, and then uses the CKY algorithm to parse a string in Chompsky Normal Form. 

## Grammars
There are two very similar grammars provided in grammar.txt and grammar2.txt. The grammar.txt grammar is

S -> AB | BC
A -> BA | a
B -> C | b
C -> BB | a

This is a simple Doty simulator compatible syntax.

This grammar can read: a

This grammar cannot read: abba

## Usage
Run the code using the default values provided using:
##### Command: python3 parser.py grammar.txt words.txt

Run the code using your own values by editing the grammar.txt file and words.txt file. 
words.txt can only take in one word in Chomsky Normal Form at a time.
##### Command: python3 parser.py grammar_file string_file
