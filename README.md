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

  - ``{ a }`` - matches the pattern exactly **n** number of times
 
  - ``{ a, }`` - matches the pattern at least **a** number of times
 
  - ``{ a, b )`` - matches the pattern from minimum of **a** number of times to a maxium of **b** number of times 

### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

Anything that is inside ``([])`` represents a range of characters that we are wanting to match.

- ``[a-z]`` - This will look for anything that is **lowercase** and any letter between **a-z**.

- ``[0-9]`` - This will look for any number 0-9.


### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
