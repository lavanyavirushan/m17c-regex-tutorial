# Regex Tutorial

This gist is a walk through of all things about Regular Expression commanly known as REGEX and how to use them. Regex is a string of text that lets you create patterns that help match, locate, and manage text. You can use to construct search strings for advanced find and/or replace searches. Perl, JavaScript, and PHP use Regex to easily find or manipulate information or to help decipher the work of other programmers. 

## Summary

We will explore how Regex is used to match Hex value. The Hex function returns a hexadecimal representation of a value as a character string. Hex
values are used for readability as well higher information density. 

In a Hex value the Regex would look something like: 

`/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`

We will explore the deatils of the anchors, quantifiers, OR Operator, Character classes, Grouping and Capturing, Bracket Expressions as well as Greedy and Lazy Match. 

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)

## Regex Components

### Anchors
2 types of anchors used: 
`^` & `$` 

Assertions come as anchors which allows you to match text without including it in the match result. The anchors can be used together within a regex to match specific group of characters on a single input line. 

`^` indicates the beginning of the string or line while `$` matches the end of a line. `#` represents the hexadecimal colour code that must start with a # symbol. 

For example: `^[a-z]$` matches the beginning and end of the expression to letters only. 

### Quantifiers
2 types of quantifiers: 
`?` & `{n}`

Quantifiers allow for flexibility in matching since it defines the number of times a character, pattern or group appears in the regex match. By default quantifiers are greedy in the sense they will try to match as many characters as they could. 


`?` matches zero or one preceding character while `{n}` creates a specific numerical quantifier range. 

For example: 
### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
