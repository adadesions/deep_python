---
description: 'In this page, I will take you tour to the world of operator. Let'' go!!'
---

# Basic Operators

## Overview

The basic operators in Python was divided into  7 categories as show below.

1. Arithmetic operators
2. Assignment operators
3. Comparison operators
4. Logical operators
5. Identity operators
6. Membership operators
7. Bitwise operators

The word basic in this topic didn't meant to 'easily' or 'simply' but fundamental operators that you must know to write python efficiently. Calm down and take a deep breath .

### 1. Arthmetic Operators

These operators always use with numerical value to do math, That's it!

| Operator | Name | Example | Output |
| :--- | :--- | :--- | :--- |
| + | Addition | 1+2 | 3 |
| - | Subtraction | 4-3 | 1 |
| \* | Multiplication | 5\*6 | 30 |
| / | Division | 1/2 | 0.5 |
| // | Floor Division | 4//2 | 2 |
| % | Modulus | 3%2 | 1 |
| \*\* | Exponentiation | 2\*\*3 | 8 |

### 2. Assignment Operators

If you want to assign some values in any datatypes to a variable, just use all of these operators.

| Operator | Example | Equivalent to |
| :--- | :--- | :--- |
| = | x = 3  | x = 3 |
| += | x += 1 | x = x+1 |
| -= | x -= 2 | x = x-2 |
| \*= | x \*= 7 | x = x\*7 |
| /= | x /= 5 | x = x/5 |
| %= | x %= 2 | x = x%2 |
| //= | x //= 9 | x = x//9 |
| \*\*= | x \*\*=2 | x = x\*\*2 |
| &= | x &= 2 | x = x&2 |
| \|= | x \|= 2 | x = x\|2 |
| ^= | x ^=2 | x = x^2 |
| &gt;&gt;= | x &gt;&gt;= 2 | x = x &gt;&gt; 2 |
| &lt;&lt;= | x &lt;&lt;= 2 | x = x &lt;&lt; 2 |

### 3. Comparison operators

If you want to compare things with is equal, greater than, or less than we usually pick "Comparison operators" to do the task.

| Operator | Name | Example |
| :--- | :--- | :--- |
| == | Equal to | x == 1 |
| != | Not Equal to | x != 3 |
| &gt; | Greater than | x &gt; 2 |
| &lt; | Less than | x &lt; 1 |
| &gt;= | Greater than or Equal to | x &gt;= 3 |
| &lt;= | Less than or Equal to | x &lt;= 10 |

### 4. Logical operators

Sometime logics is the heart of problem solving, these operators help us to use logic in our appication.

| Operator | in other languages | Example |
| :--- | :--- | :--- |
| and | && | \(x &gt; 3\) and \(x &lt; 10\) |
| or | \|\| | \(x == 2\) or \(x == 4\) |
| not | ! | not \(x &lt; 3 \) |

**The Truth table**  
Just in case, you had threw away all mathematical logics, let me remind you.

{% hint style="info" %}
**AND Table**  
Just remember that only "one case" is True,  
\( True and True \) is True, otherwise False.

**p    q    p and q**

**============**

**T    T        T**

**T    F        F**

**F    T        F**

**F    F        F**

**============**
{% endhint %}

{% hint style="info" %}
**OR Table**  
Just remember that only "one case" is False,  
\( False and False \) is Flase, otherwise True.

**p    q    p or q**

**============**

**T    T        T**

**T    F        T**

**F    T        T**

**F    F       F**

**============**
{% endhint %}

{% hint style="info" %}
**Not Table**  
The opporsite value, That's it!

**p           not p**

**============**

**T              F**

**============**

**in other hand,**

**q           not q**

**============**

**F              T**

**============**
{% endhint %}

### 5. Identity Operators

This type of operator quite different from the most programming in market because the operator can help us in checking equality of variable.

| Operator | Description | Example |
| :--- | :--- | :--- |
| is | if two variables are the same return True | x is y |
| is not | if two variables are not the same return True | x is not y |

### 6. Membership Operators

Membership operators are useful in Python and make it has more benefits than others. Its purpose is to check is the object present in a sequence.

| Operators | Description | Example | Output |
| :--- | :--- | :--- | :--- |
| in | If the object in a sequence return True | 2 in \[1, 2, 3\] | True |
| not in  | If the object is not in a requence return True | 2 not in \[ 1, 3, 5\] | True |

### 7. Bitwise Operators \( Optional \)

Bitwise operators whose operators to deal with bit level. Truth be told that the operators are not considering in beginner level but to cover all operators in Python I have to introduce you to this operators.

{% hint style="warning" %}
**Binary Numeral System \(required\)**

To deal with bits you must strong in Binay number, if not?  
Don't worry I will take you tour a bit in Binary number

**Binary Numberal System** is contain only two numnbers

**0** and **1**

**For instance,**  
$$0_{10} = 0000_2$$   
$$2_{10} = 0010_2$$  
$$4_{10} = 0100_2$$   
$$8_{10} = 1000_2$$   


See somethings right?
{% endhint %}

{% hint style="danger" %}
**Keep in mind**, Bitwise operators is quite similar to logic operators but differ in some points.

**0** represented to **False**   
**1** represented to **True**
{% endhint %}

<table>
  <thead>
    <tr>
      <th style="text-align:left">Operator</th>
      <th style="text-align:left">Name</th>
      <th style="text-align:left">Description</th>
      <th style="text-align:left"><b>Example</b>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">&</td>
      <td style="text-align:left">AND</td>
      <td style="text-align:left">Sets each positions to 1, if both are 1</td>
      <td style="text-align:left">101 & 001 = 001</td>
    </tr>
    <tr>
      <td style="text-align:left">|</td>
      <td style="text-align:left">OR</td>
      <td style="text-align:left">Sets each positions to 1, if both are at least 1</td>
      <td style="text-align:left">101 | 001 = 101</td>
    </tr>
    <tr>
      <td style="text-align:left">^</td>
      <td style="text-align:left">XOR</td>
      <td style="text-align:left">Sets each positions to 1, if only one is 1</td>
      <td style="text-align:left">101 ^ 001 = 100</td>
    </tr>
    <tr>
      <td style="text-align:left">~</td>
      <td style="text-align:left">NOT</td>
      <td style="text-align:left">Invert all positions</td>
      <td style="text-align:left">~101 = 010</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <<</td>
          <td style="text-align:left">Zero fill left shift</td>
          <td style="text-align:left">Shift left by pushing zeros in from the right and let the leftmost bits
            fall off</td>
          <td style="text-align:left">010
            << 1 <br />= 100</td>
    </tr>
    <tr>
      <td style="text-align:left">>></td>
      <td style="text-align:left">Zero fill right shift</td>
      <td style="text-align:left">Shift right by pushing copies of the leftmost bit in from the left, and
        let the rightmost bits fall off</td>
      <td style="text-align:left">
        <p>010 >> 1</p>
        <p>= 001</p>
      </td>
    </tr>
  </tbody>
</table>### Exercise and Problems

