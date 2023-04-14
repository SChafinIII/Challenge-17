# Matching an Email – /^([a-z0-9_.-]+)@([\da-z.-]+).([a-z.]{2,6})$/

## Introduction

Welcome to this tutorial on matching an email address using regular expressions. In this tutorial, we will be exploring a specific regular expression that can be used to match valid email addresses. We will break down each component of the regular expression and explain what it does.

## Summary

The regular expression we will be discussing is /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/. This regex pattern can be used to validate email addresses. It uses different components like character classes, quantifiers, and anchors to define a specific search pattern.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)


## Regex Components

### Anchors
Anchors are used to match a position in the text rather than a character. In our email regex, the ^ anchor is used at the beginning of the pattern to match the start of the line, and the $ anchor is used at the end to match the end of the line. This ensures that the email address is matched in its entirety and not just as part of a larger string.

### Quantifiers
Quantifiers are used to specify the number of occurrences of a pattern. In our email regex, the + quantifier is used to indicate that one or more characters must appear before the @ symbol and the {2,6} quantifier is used to specify that the top-level domain can be between 2 to 6 characters long.

### Character Classes
Character classes are used to match a single character from a set of characters. In our email regex, the character classes a-z, 0-9, _, ., and - are used to match specific characters that are allowed in email addresses.

### Grouping and Capturing
Grouping is used to group together different parts of the pattern. In our email regex, we use parentheses () to group the username, domain, and top-level domain separately. Capturing is used to save the matched content for later use. In our email regex, the matched groups can be captured and used separately in the code.

### Bracket Expressions
Bracket expressions are used to match any single character within a specified range or set of characters. In our email regex, the expression [\da-z\.-] matches any digit (\d), lowercase letter (a-z), or period (.) or hyphen (-) symbol.

## Author

This tutorial was written by Steven Chafin III a Fullstack Bootcamp student at the University of Kansas. You can learn more about me on my [GitHub Profile](https://github.com/SChafinIII)
