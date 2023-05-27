# Title (replace with your title)

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

Anchors are used to indicate the beginning or end of a match. The carat "^" anchor matches the beginning of the string, and the dollar sign "$" indicates the end.

`^banana$`

### Quantifiers

Quantifiers indicate how many times a character or group of characters should be matched. The most common quantifiers are:

* matches zero or more times
+ matches one or more times
? matches zero or one time

Code snippet that matches any string that consists of one or more letters.

`[ba-na-na]+` 

### OR Operator

The OR operator is used to match any of a set of characters. The OR operator is represented by the pipe character (|)

code snippet

'ba-na-na|0-9'

### Character Classes

Character classes are used to specify a set of characters that should be matched. Character classes are enclosed in square brackets ([]).

`[ba-na-na]`

### Flags

Flags are used to modify the behavior of a regular expression. The most common flags are:

i makes the regular expression case-insensitive
m makes the regular expression match multiple lines

code snippet 

`^[ba-na-na]+$`

### Grouping and Capturing

Grouping is used to group together a set of characters. Captured groups can be referred to later in the regular expression.

code snippet 

`(.*) (.*)`

### Bracket Expressions

Bracket expressions are used to match a specific character or range of characters. Bracket expressions are enclosed in square brackets ([]).

code snippet

`[ba-na-na]`

### Greedy and Lazy Match

Greedy matches as many characters as possible, while lazy matches as few characters as possible. The default match type is greedy.

code snippet

`.*`

### Boundaries

Boundaries are used to match the beginning or end of a word, a line, or a character class. The most common boundaries are:

\b matches the beginning or end of a word
\n matches the end of a line
\s matches a whitespace character

`\b[ba-na-na]+\b` 

### Back-references

Back-references are used to refer to a captured group. Back-references are enclosed in backticks (`).

For example, the regular expression (banana) (banana) matches two words, and the first word is captured in the first group and the second word is captured in the second group. The regular expression \1 \2 will then print the two words, separated by a space.

code snippet

`(banana) (banana)`

### Look-ahead and Look-behind

Look-ahead and look-behind are used to match a pattern that occurs before or after the current position. Look-ahead is denoted by (?=pattern), and look-behind is denoted by (?<=pattern).

code snippet

'(?<=^[ba-na-na)[ba-na-na]+'

Author
This document was written by a student who had no idea what they were doing.


A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
