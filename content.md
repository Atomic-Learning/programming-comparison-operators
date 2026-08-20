# What are Comparison Operators?

Comparison operators are used to compare two values and produce a boolean result—either `true` or `false`. They are fundamental to programming because they allow us to make decisions based on the values of variables and expressions.

For example, consider the following expression:

```
a < b
```

Here, the variables `a` and `b` are being compared. The comparison operator `<` checks if the left value is less than the right value.

# Common Comparison Operators

Most programming languages support the following comparison operators (the exact characters used for the operators will vary between languages):

* `<` (less than): Returns `true` if the left value is less than the right value
* `>` (greater than): Returns `true` if the left value is greater than the right value
* `<=` (less than or equal to): Returns `true` if the left value is less than or equal to the right value
* `>=` (greater than or equal to): Returns `true` if the left value is greater than or equal to the right value
* `==` (equal to): Returns `true` if the two values are equal
* `!=` (not equal to): Returns `true` if the two values are not equal

# Comparing Different Types

Comparison operators typically work with numeric values (integers and floating-point numbers). In many languages, they can also be used with strings, where the comparison is based on alphabetical order. The behaviour of comparisons with other data types varies between languages.

# Examples Using Pseudocode

Here are some examples of comparisons written in pseudocode:

```
a = 5
b = 3

a < b  → false // 5 is not less than 3
a > b  → true // 5 is greater than 3
a == b → false // 5 is not equal to 3
a != b → true // 5 is not equal to 3
a <= 5 → true // 5 is less than or equal to 5
a >= 5 → true // 5 is greater than or equal to 5
```
