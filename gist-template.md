# Regex-Email-Tutorial
Often many of us have not thought about it, but our emails are comprised of a pattern that our software uses to see if it is valid. This pattern is called a regular expression or regex as it is known by many developers. Regular expressions search an input from a user, this can be very helpful in simplifying code for a programmer. Thats exactly what happens when you input your email or create a new one and thats exactly what will explained on this page. 

## Summary
The regular expression that I will explaining today is the one that makes up an email (`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`). I will be going over the characters of the expression and how they work together to allow emails to work. 

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
For reference, this is the email regex: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

### Anchors
^ and $ at the beginning and end of the expression, signifies the pattern to look at everything in between them.

### Quantifiers
"+" adds the values within the parentheses
{2,6} check the length of the string between 2 and 6 characters.

### OR Operator
There are no OR Operators in this regex.

### Character Classes
\d Matches any digit character (0-9). Equivalent to [0-9]. This can be seen in the second group of the expression.

### Flags
There are no flags in this expression.

### Grouping and Capturing
() captures the grouping of characters, character classes, and quantifiers. In this expression, it is specifically capturing the information within the [], the "+" which adds the groups together, and in the last group there is a quantifier {}. There is also an @ sign that is sandwiched between the first to group to signify the seperation of the two.

### Bracket Expressions
[] chooses any of the characters within the brackets. In the first group it is any letter in the alphabet, any digit, with special characters (_\.-).

### Greedy and Lazy Match
This expression has no greedy or lazy matches.

### Boundaries
There are no boundaries stated in this expression.

### Back-references
This expression has no back references.

### Look-ahead and Look-behind
This expression has no look-ahead or look-behind components.

## Author
My name is Mark Protsyuk and I am a software developer from the bay area. I have only been programming for a little less than a year. I have recently leared how to read a Regex string and had a lot of fun describing it!

GitHub: https://github.com/MrProtsyuk

