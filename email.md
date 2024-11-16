# Email Regex Explanation

This tutorial will examine and breakdown the the search query for an email.

## Summary

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

The email search query above is a perfect example on how to explain regex search patterns. In this tutorial we will breakdown what the different symbols mean.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors

The above example has 2 anchors. the first anchor is the `^` symbol. This symbol indicates a string that begins with the characters that follow. This means that in the code `^regex`, the search would include anything with "regex" in the search. 

Meanwhile, the `$` is similar to the `^` however it indicates a search that ends with anything before it. For example, `regex$` will search for anything that ends with "regex". 

### Quantifiers

The above example also includes `{2,6}`

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author