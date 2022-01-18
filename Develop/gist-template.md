# Regex Tutorial : Match URL with Regular Expressions (Regex)

URL Regex: A regualr or rathional expression defined as characters in a pattern or a sequence that replace or find string operations which may be useful locating a string in a URL.

## Summary

A Regex is useful in matching a URL in order to locate special text patterns.

```
https?:\/\/(www\.)?[\d-a-zA-Z0-9@:%._\+~#=]{1,256}\.[a-zA-Z0-9()]{1,6}\b([-a-zA-Z0-9()@:%_\+.~#?&//=]*)
```

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

Anchors are used at the beginning and end of searches to check if a string matches a certain pattern, however they themselves do not match any characters. They are there to affirm a string matches a location. Achors will create parameters. 
* Use the ```^``` anchor to match the beginning of the text. 
* Use the ```$``` anchor to match the end of the text.

### Quantifiers

Quantifiers will measure and set the limit on the number of characters that we are wanting to match our Regex:
* ```+``` Searches the pattern one or more times,
* ```?``` Searches the pattern zero or one time
* ```*``` Searches the pattern zero or more times
* ``` https? ``` for example. The ? will make the preceeding time optional.


### OR Operator

The OR operator's purpose is to match the characters on the left or right of the operator, serving as an or, as in and/or. Using the | as in m|M would match either m or an M from the string. If we had used https?:\/\/(www\.)?[\d-a|A it would search for a OR A.

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
