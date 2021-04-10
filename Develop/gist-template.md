# WELCOME TO MY REGEX TUTORIAL

Introductory paragraph
Welcome to Matching a Hex value you with reggex expresions, I am going to be giving you a break down of the 'Hex value' expression.

## Summary

"I Will be covering the regex expression 'Hex value',and how to create and read the expression as well as a break down Matching a Hex Value &ndash; `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components
`/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`.

### Anchors
    Now the Anchors that are with this expression are as follows
    "^"- this anchor is the beginning of an empty string
    "$"- this anchor signals an end to a string
    "\b"- this signals a word boundry
    "\B"- this signals not a word boundary


### Quantifiers
 Now the Quantifiers for this expression matches the specified quanity of the previous token. {1,3} will match 1 to 3. {3} will match exactly 3. {3,} will match or more.
### OR Operator



### Character Classes
 the only charcter class with this expression would be the "#" char 35
### Flags

### Grouping and Capturing
groups multiple tokens together and creates a capture group
for extracting a substring or using a backreference and example of 
this would be "(ha) +".
THE Capturing group for this expression is "(ABC)
THE A-f range matchs a  character in the range "a" to "f"(char code 97 to 102) , and they are case senstive.
and also the 0-9 range. and that matches a characer in the range "0" to "9"(char code 48 to 57). and those are case sensitve as well.



### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
