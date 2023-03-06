# Validating Email Address Regex

This Gist provides an explanation of the regular expression `/[A-Z0-9._%+-]+@[A-Z0-9-]+.+.[A-Z]{2,4}/igm` for validating email addresses. 

## Summary

This regex checks for the syntax of an email address, ensuring that it includes an @ symbol, a valid domain name, and a valid top-level domain code. It also allows for the use of uppercase and lowercase letters, digits, and special characters in the local part of the email address.


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

This regex does not include any anchor characters.

### Quantifiers

This regex includes the `+` quantifier, which matches one or more of the preceding token. 

### OR Operator

This regex does not include an OR operator.

### Character Classes

This regex includes several character classes, including:
- `[A-Z]`: Matches any uppercase letter
- `[a-z]`: Matches any lowercase letter
- `[0-9]`: Matches any digit
- `[_%+-]`: Matches any of the special characters "_", "%", "+", and "-"
- `[-]`: Matches a hyphen

### Flags

This regex includes several flags:
- `i`: Enables case-insensitive matching
- `g`: Matches all occurrences of the pattern in a string
- `m`: Enables multiline mode

### Grouping and Capturing

This regex does not include any capturing groups.

### Bracket Expressions

This regex includes a bracket expression that matches any character except for line breaks (`.`).

### Greedy and Lazy Match

This regex uses greedy matching, which means it will match as much of the string as possible while still allowing the entire pattern to match.

### Boundaries

This regex does not include any boundary characters.

### Back-references

This regex does not include any back-references.

### Look-ahead and Look-behind

This regex does not include any look-ahead or look-behind assertions.

## Author

This Gist was created by Athena King here is my github link https://github.com/Azrael-Savage


