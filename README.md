# Regex Tutorial - Matching an Email

This Regex tutorial will explain and breakdown understanding the regular expression of "matching an email".

"/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/"

## Summary

The term regular expression is a sequence of characters that defines a search pattern. Commomnly used to find patterns inside a string and or replace characters or validate input. In this tutorial it will demonstrate the components of a regex and how it applies to matching an email.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)

## Regex Components

### Anchors
In this regex expression for matching an email are `^`, this indicates the start of the string while `$` indicates the end of the string.

### Quantifiers
The Quantifiers in this regex are the `+` operator, which connects the users email name + email + .com. Another quantifier would be `{2,6}` it allows a match range of 2-6 characters for the set of `[a-z\.]`.


### Character Classes
The character class in the expression is `/d`, which matches a single character and the digit ranges from 0-9. 

### Grouping and Capturing


### Bracket Expressions

### Greedy and Lazy Match

## Author

My projects can be viewed at https://github.com/Dapr1nc3 