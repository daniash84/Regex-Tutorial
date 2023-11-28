# Regex-Tutorial

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

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

### Anchors
anchors signigies a string, where the string is "The" or "The Person"
/^[a-z0-9_-]{3,16}$/

### Quantifiers
set the limits of the string that your regex matches (or an individual section of the string).
### OR Operator
bracket expression does not require the string to meet all of the requirements in the pattern
(abc):(xyz) == (a|b|c):(x|y|z)

### Character Classes
defines a set of characters, any one of which can occur in an input string to fulfill a match

### Flags
are placed at the end of a regex, after the second slash, and they define additional functionality or limits for the regex - they are the exception to the regex must being wrapped in slash characters

### Grouping and Capturing
grouping is regex is a way to break up the sections of a complicated regex by using (())

### Bracket Expressions
A bracket expression (an expression enclosed in square brackets, "[]" ) 

### Greedy and Lazy Match
Lazy mode - “repeat minimal number of times”.
Greedy - 
### Boundaries
 the position between a word and a non-word character, or vice versa
 -\b
### Back-references
is a way to match the same text as previously matched by a capturing group 

### Look-ahead and Look-behind
positive lookahead, negative lookahead, positive lookbehind, and negative lookbehind assertions

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile) - x(?= y)