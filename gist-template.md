# Regex Tutorial (Matching an Email)

This is a tutorial on using regex to match a email. Regex is also known as regular expressions, it is very useful on retrieving information from any text within a coding environment. 

## Summary

I will be focusing on the email validation regex. /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ will be the template that I use in this example. Through learning regex, the knowledge can be applied to many different places, including validation for parsing, replacing strings, passing through translating data etc.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)

## Regex Components

### Anchors

    /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

    Anchor marks the beginning and the end of a regex, by using ^ to start an expression, and $ to close it. You can see from the example provided that it begins with ^ and ends with $.

### Quantifiers

    /[a-z0-9_\.-]+/

    Quantifiers determines how often an element can appear. So in the example above the expression uses + to determine that the element in front can appear by one or more times.

### Character Classes

    /([\da-z\.-]+)/

    character classes determines what characters can be used in that expression, as for example above the \d means that the elements can be digits.

### Grouping and Capturing

    /([\da-z\.-]+)/

    grouping and capturing will group together a regex, so it is very useful to extract information from data and strings. It is a way to keep the regex organized and easy to search for.

### Bracket Expressions

    /([a-z0-9_\.-]+)@([\da-z\.-]+)/

    OR operator determines what follows after the first expression, so you can see in the example above and see that [] is used before and after the @ sign, which determines that one follows the other to ensure the order is correct.

## Author

Alan Lin GitHub: https://github.com/alan6120404
