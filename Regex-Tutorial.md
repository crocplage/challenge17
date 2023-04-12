# Regex in Javascript

A regular expression is a sequence of characters that forms a search pattern.

The search pattern can be used for text search and text replace operations.

(source:w3schools.com)

## Summary
In this Tutorial we going to see the meaning of each expression meaning Hex values, which is used to descripe a colot in a computer language. it starts with the value #, our exemple : /^#?([a-f0-9]{6}|[a-f0-9]{3})$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors
^ $ they are anchors ^ matches the start of a string, $ matches the end of the string.

### Quantifiers
? {6} {3}
Quantifiers are used to determine the number of characters allowed, {6} stands for Hex format six digit code (Hexa is 6 in Greek), {3} shorthand for Hexadecimal color code from A to F , A = 10 , B = 11 ...
? it depends on the context it appears in this exemple it means 0 or 1 as we have two options {6} {6}, it can be used in different context ex: colou?r , we can say either color (us) or colour (uk)

### OR Operator
|  this element defines OR for exemple man|woman matches either a man or a women

### Character Classes
[a-f0-9] [a-f0-9]
Charactrer classes are the type of characters allowed in the expression, a,b,c,d,e,f with are the hexadecimal matching the set of numbers 10 to 15
and 0-9 numbers allowed from 0 to 9

### Grouping and Capturing
It doesnt apply to our exemple, 
it allows to match what's inside ()
### Bracket Expressions
bracket expressions allow to match a single character from specific set of characters,exemple  [0o] matches no, n0, NO, [0-9] matches any digit fom 0to 9, 
### Greedy and Lazy Match
greedy operator tries to match as many times as possible ex: `a.*b` matches the string 'aBcdEfGhIjKb'
Lazy operator tries to match as little as possible we add '?'
### Boundaries
Bundaries are used to match start and end withing the string , exemple : 

### Look-ahead and Look-behind
allow you to match patterns based on what comes before or after a certain point in the string, without actually including those characters in the match
## Author

Hello, I'm Kam Github : crocplage