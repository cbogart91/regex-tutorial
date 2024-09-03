# Regex (Regular Expression) Tutorial

Regular expressions, or regex, is a series of special characters that define a search pattern. 

## Summary

This tutorial will go over the components of regex and for example, the below code is a regular expression which is called "Matching a Username":

``/^[a-z0-9_-]{3,16}$/``

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

There are two characters, ``^`` and ``$`` that are both considered **anchors**.

- ``^`` - signifies a string that begins with the characters that follow it.

- ``$`` - signifies a string that ends with the characters that precede it.


### Quantifiers

The string is limited that your regex matches which is called **quantifiers**.

- ``*`` - matches the pattern zero or more times.

- ``+`` - matches the pattern one or more times.

- ``?`` - matches the patter zero or one time.

- ``{}`` - curly brackets provide three different ways to set limits for a match:

  - ``{ a }`` - matches the pattern exactly **n** number of times.
 
  - ``{ a, }`` - matches the pattern at least **a** number of times.
 
  - ``{ a, b )`` - matches the pattern from minimum of **a** number of times to a maxium of **b** number of times.

### OR Operator

### Character Classes

In a regex character class is a set of characters where any one of which can occur in an input string to fulfill a match.

 - ``.``

### Flags

Flags define additional functionality or limits for the regex which are placed at the end after the second slash.

- ``g`` - global search: the regex should be tested against all possible matches in a string.

- ``i`` - case-insensitive search: case should be ignored while attempting a match in a string.

- ``m`` - multi-line search: case should be treated as multiple lines.

### Grouping and Capturing

### Bracket Expressions

Anything that is inside ``([])`` represents a range of characters that we are wanting to match.

- ``[a-z]`` - This will look for anything that is **lowercase** and any letter between **a-z**.

- ``[0-9]`` - This will look for any number 0-9.


### Greedy and Lazy Match

Greedy means they match as many occurences of particular patterns as possible which includes the **quantifiers**.

Lazy match means they will match as few occurrences as possible by just adding **?** symbol after the **quantifiers**.


### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
