# REGEX: A Brief Description

This document is a brief dive into what a regular expression (regex) is, and how it is used. 

## Summary

A regular expression, or regex, is a sequence of characters that forms a search pattern. Regex is used for string pattern matching and manipulation. An example of a regex that matches any string containing 'hello' would be `/hello/`.

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

Anchors are used to specify the position of the pattern in relation to a line of text. `^` represents the start of a line, while `$` represents the end.

### Quantifiers

Quantifiers specify how many instances of a character, group, or character class must be present in the input for a match to be found. `a*`, for example, matches any number of 'a' characters, including zero.

### Grouping Constructs

Grouping constructs are used to define the scope and precedence of the operators in the pattern. `(abc)`, for example, groups 'a', 'b', and 'c' together as a unit.

### Bracket Expressions

Bracket expressions are used to define a character class, a set of characters to match. `[abc]`, in this example, matches any character from the set of characters {'a', 'b', 'c'}.

### Character Classes

Character classes are used to match any one of a set of characters. `/d` is used to match any digit.

### The OR Operator

The OR operator is represented by `|`. It is used to match the pattern before OR pattern after it. `1|2` matches '1' or '2'.

### Flags

Flags are used to control the behavior of the regex. The `g` flag is used for global search and `i` is used for case-insensitive search. 

### Character Escapes

Character escapes are used to allow for special characters to be used as search characters. `\@` is used to match the '@' symbol.

## Author

Regex: A brief definition was authored by [dsatpm](https://www.github.com/dsatpm). I (dsatpm) have been thoroughly enjoying 'Ghost of Tsushima' for PS5, learning classic death metal tracks on guitar (Nile, Cannibal Corpse, Deicide), and coding, coding, coding!!
