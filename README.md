# Regex-Tutorial
Regular expressions (Regex) are patterns used to match character combinations in strings. This tutorial explains the email regex by breaking down each part of the expression.

## Summary
The following regular expression can be used to verify that user input is a valid email address:

```
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
```

