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
In this expression capturing group #1 is `([a-z0-9_\.-]+)` this matches the users email name. Capturing group #2 is `([\da-z\.-]+)` this matches the email service that is used. The 3rd capturing group is `([a-z\.]{2,6})` it captures the .com of the email address. 


### Bracket Expressions
In bracket expressions for validating emails the charcter sets include `[a-z0-9_\.-]`, It matches any letter a-z also being case senstive. Also matches a character between 0-9 and characters such as "_", "-" and ".". `[\da-z\.-]`, matches a single digit from 0-9, any character from a-z. Then the characters "." & "-", `[a-z\.]`.

### Greedy and Lazy Match
In this regex it has greedy matches since there is a `+` quantifier it matches as many times as possible. Another greedy quantifier used is `{}` when matching `{2,6}` for the last capture group.

## Author
My projects can be viewed at https://github.com/Dapr1nc3 