---
layout: post
title: ET Operator Precedence
---

The following table lists the precedence and associativity of **ET** operators.

Operators are listed top to bottom, in descending precedence.



| Precedence  | Operator | Description | Associativity |
| ------------- | ------------- | ------------ | ---------- |
| 1 | ++<br>--<br>()<br>[] | Suffix/Postfix increment<br>Suffix/Postfix decrement<br>Function call<br>Array subscripting | Left-to-right |
| 2 | +<br>-<br>!<br>~<br>& | Unary plus<br>Unary minus<br>Logical NOT<br>Bitwise NOT<br>Address-of | Right-to-left |
| 3 | ** | Pow | Left-to-right |
| 4 | *<br>/<br>% | Multiplication<br>Division<br>Remainder | Left-to-right |
| 5 | +<br>- | Addition<br>Subtraction | Left-to-right |
| 6 | \<<<br>\>> | Bitwise left shift<br>Bitwise right shift | Left-to-right |
| 7 | < <br><=<br>><br>>= | For relational operators < respectively<br>For relational operators ≤ respectively<br>For relational operators > respectively<br>For relational operators ≥ respectively | Left-to-right |
| 8 | ==<br>!= | For relational = <br>For relational ≠ | Left-to-right |
| 9 | && | Logical AND | Left-to-right |
| 10 | \|\| | Logical OR | Left-to-right |
| 11 | ^ | | |
