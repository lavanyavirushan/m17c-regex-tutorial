# Regex Tutorial

This gist is a walk through of all things about Regular Expression commanly known as REGEX and how to use them. Regex is a string of text that lets you create patterns that help match, locate, and manage text. You can use to construct search strings for advanced find and/or replace searches. Perl, JavaScript, and PHP use Regex to easily find or manipulate information or to help decipher the work of other programmers. 

## Summary

We will explore how Regex is used to match Hex value. The Hex function returns a hexadecimal representation of a value as a character string. Hex
values are used for readability as well higher information density. 

In a Hex value the Regex would look something like: 

`/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`

We will explore the deatils of the anchors, quantifiers, OR Operator, Character classes & Grouping. 

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes & Grouping](#character-classes-grouping)

## Regex Components

### Anchors

2 types of Anchors used: 
`^` & `$` 

Assertions come as anchors which allows you to match text without including it in the match result. The anchors can be used together within a regex to match specific group of characters on a single input line. 

`^` indicates the beginning of the string or line while `$` matches the end of a line. `#` represents the hexadecimal colour code that must start with a # symbol. 

For example: `^[a-z]$` matches the beginning and end of the expression to letters only. 

### Quantifiers

2 types of Quantifiers: 
`?` & `{n}`

Quantifiers allow for flexibility in matching since it defines the number of times a character, pattern or group appears in the regex match. By default quantifiers are greedy in the sense they will try to match as many characters as they could. 

`?` matches zero or one preceding character while `{n}` creates a specific numerical quantifier range. 

### OR Operator

1 type of OR Operator: `|` 

OR Operator tell the regex to look at one or the other group of expression of {n} character hex value. 

For example: `[a-f0-9]{6}|[a-f0-9]{3}` it will look at {6} character value or {3} in either expression group. 

### Character Classes and Grouping 

1 type of Character Class: `[a-f0-9]` 
1 type of Grouping: `([a-f0-9]{6}|[a-f0-9]{3})`

Character class is a set of chacters enclosed within a sqauare brackets. It specfies the characters that will successfully match a single character from a given string or range. 

Grouping is a specific set of character that will match any character inside it. `[]` creates a character group or range while `()` creates a sequence or sub-expression. It will often be used in combination with an OR Operator.  

For example: `[a-f0-9]` we have 2 ranges where it will match lowercase characters "a" through "f" as well as "0" through "9". 

### Flags

Flags are optional parameter to a regex that modifies its behaviour of searching. It can change the default searching behaviour and is represented using lowercase alphabetic characters. 

## Author

Lavanya Virushan 
Current UofT Bootcamp student working towards completing a certification. 

[Github](https://github.com/lavanyavirushan): LavanyaVirushan
