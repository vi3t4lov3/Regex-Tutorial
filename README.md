# Regex-Tutorial
Regular expressions (Regex) are patterns used to match character combinations in strings. This tutorial explains the email regex by breaking down each part of the expression.

## Summary
The following regular expression can be used to verify that user input is a valid email address:

```
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
```



### Anchors
Anchors are used to “anchor” the regex match at a certain position.
`^` matches the position before the first character in the string from the email, and `$` matches right after the last character in the string.

### Quantifiers
Quantifiers indicate numbers of characters or expressions to match. 
`{}` is the quantifiers in this expressrion. 
`{2,6}` here means to check if the eamil domain `.xx` has 2 to 6 letters.

### OR Operator
OR Operator `|` indicates the logical "or".
It doesn't have one here but you will use it in building a logical “or” operation using regular expressions.

