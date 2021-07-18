# Regex E-mail Tutorial

This tutorial will be covering the step by step process of useing regex to 
validate an e-mail address.

## Summary

The regex for an e-mail address should look something like this 
{/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/}. But what does all that mean?
In this tutorial we are going to go over the step by step process of creating
a regex for validating an e-mail. You will learn what each symbol means and
what they do.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)

## Regex Components

### Anchors

Anchors are the starting and the end point of the regex expression.{/^} being the start of en expression. While the dolar sighn {$/} is the end of an expression.

### Quantifiers

The quantifier used in this expression is used to range the length of the e-mail 
after the {.} in the e-mail. the quantifier looks like this {2,6} ranging the number of characters aloud from 2 to 6.

### Character Classes

character classes are used to identifiy characters useing brackets {[a-z]}. You can use this to identify 1 or more letters or use the hyphen to search a set of letters from the alphebet. in our e-mail we are useing {[a-z]} to find or allow all the letters in the alphabet.

### Flags

Flags are used to tell javascript we are creating a regular expression. The flags used in our e-mail regex is a back slash at the begining and end. {/}

### Grouping and Capturing

Grouping is using parentheses to group part of the regex together. That allows you to put a quantifier for the entire group. The paraentheses also capture the group by storing the part of the string matched by the reguler expression. 

### Bracket Expressions

A bracket expression is a list of characters inside of brackets. {[]} It matches any single character in the bracket list.

### Greedy and Lazy Match

Greedy matches the longest possible string. While lazt matches the shortest possible string. In the e-mail regex the plus sighn is used to be greedy. A question mark would be used to be lazy but not needed in our expression.

## Author
By Dylan Green
Github profile link https://github.com/dylgrn
A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
