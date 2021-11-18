# Regex Tutorial: Pattern Title

This is a regular expression for validating email address inputs. This expression will validate that emails are being entered in proper formatting and use common characters

## Summary

I'll describe this regular expression

$([a-zA-Z0-9_\-\.]+)@([a-zA-Z0-9_\-\.]-)\.([a-zA-Z]{4,10})$

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Bracket Expressions](#bracket-expressions)
- [Character Escapes](#character-escapes)

## Regex Components

This expression has three sections defined by the different bracket groups
[a-zA-Z0-9_\-\.]
[a-zA-Z0-9_\-\.]
[a-zA-Z]
Inside the brackets will also check for uppercase and lowercase characters and numeric values which are called character classes a-z A-Z 0-9

### Anchors

$ and $
Start and end points of the expression

### Quantifiers

They are located inside () and outside the brackets
+, - and {4,10}

### Bracket Expressions

[a-zA-Z0-9_\-\.]
and
[a-zA-Z]

### Character Escapes

\- and \.

## Author

Jordan Lindgren [GitHub profile](https://github.com/jordanlindgren).
