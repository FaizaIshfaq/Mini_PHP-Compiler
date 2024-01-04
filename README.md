# Mini_PHP-Compiler
Mini PHP Compiler with Syntax, Lexical, and Symbol Table Implementation using automated tool LEX and YACC
It is a case insensitive language.
This project implements the following:
1. Implement the lexical analysis phase.
2. Implement the syntax analysis phase.
3. Implement symbol table manager (Register Variables).
5. Report error in case of error (lex, syntax).
A source file “source.txt” containing the source
code of “Mini PHP” as input.
It writes all the tokens <TokenType, Lemexe> in
separate file “token.txt”.
It writes all the Identifiers in a separate file
“Identifier.txt”.
If the code is successfully parsed show the given
message
“Code Compiled Successfully”
If the code carries an error it displays the message
“Code cannot be compiled ” and also displays the
type and line number of error.
