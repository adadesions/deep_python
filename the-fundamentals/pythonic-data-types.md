---
description: >-
  This page is all about Data Types in Python language. You will found yourself
  around with amazing things!
---

# Pythonic Data types

## Data Types

The first things that I want all of you to keep in your mind is...

> **Python is Python, Not Java, C++, or other programming language.**

**Why?**

Because I want you to focus on python not to compare with other languages. Every languages has it own principle, philosophy, and syntax so, do not compare just use it as it has to be.

| Data Type | Example |
| :--- | :--- |
| Integers | 1, 2, 3 |
| Float | 1.1, 3.00004, 4.05e-3 |
| Complex | 1+5j, 3-1j, 100+9j |
| Strings | "AdaBrain", "SUT", "Python" |
| Boolean | TRUE, FALSE |

### Integers

> &lt; class 'int' &gt;

In Python, we have vary integer forms depending on what number you would like to use

**Decimal base**

The decimal base we always use it in our daily life so not thing much about just 0-9, an integer in Python 3.x support long integer or big integer it's mean that you can calculate a big integer as big as your memory can handle it.

For example,

{% code-tabs %}
{% code-tabs-item title="Decimal Base" %}
```python
print(1)
print(15)
print(12345678912345678912345678912345678912345678912345678)
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="OUTPUT" %}
```python
1
15
12345678912345678912345678912345678912345678912345678
```
{% endcode-tabs-item %}
{% endcode-tabs %}

**Binary base**

This base is contain only two number are "0" and "1" the integer class provided binary base  ****as show below

{% hint style="success" %}
**Syntax!**

0b        zero + lower letter 'b'

0**B**        zero + capital letter 'B'
{% endhint %}

For example, 

{% code-tabs %}
{% code-tabs-item title="Binary Base" %}
```python
print(0b101)
print(0b1011)
print(0b100001)
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="OUTPUT" %}
```python
5
11
33
```
{% endcode-tabs-item %}
{% endcode-tabs %}

**Octal base**

Octal base number system, it's a system that contain numbers 0 to 7

{% hint style="success" %}
**Syntax!**

0o        zero + lower letter 'o'

0O        zero + capital letter 'O'
{% endhint %}

\*I recommend you to type lower 'o' rather than a capital one

For example, 

{% code-tabs %}
{% code-tabs-item title="Octal Base" %}
```python
print(0o13)
print(0o20)
print(0o777)
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="OUTPUT" %}
```python
11
16
511
```
{% endcode-tabs-item %}
{% endcode-tabs %}

**Hexadecimal base**

Hexadeciaml base number system, it's a system that contain numbers 0 to 9 and added A-F in the number system

{% hint style="success" %}
**Syntax!**

0x        zero + lower letter 'x'

0X        zero + capital letter 'X'
{% endhint %}

For example, 

{% code-tabs %}
{% code-tabs-item title="Hexadeciamal Base" %}
```python
print(0x2)
print(0x1)
print(0x7C8)
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="OUTPUT" %}
```python
2
1
1992
```
{% endcode-tabs-item %}
{% endcode-tabs %}

### Floating-Points

> &lt; class 'float' &gt;

In Python, Floating-point was designed by according to the IEEE 754 it represent float value as 64 bits "double-precision" that made Python can approximately the maximum value to $$1.8  \times 10^{308}$$ if exceed the value Python will handle those number as ' inf '

For example,

{% code-tabs %}
{% code-tabs-item title="Floating-Points" %}
```python
print(1.23)
print(1.8e307)
print(1.8e308)
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="OUTPUT" %}
```bash
1.23
1.8e+307
inf
```
{% endcode-tabs-item %}
{% endcode-tabs %}

The limitation and issues of floating-points in Python  
[https://docs.python.org/3.6/tutorial/floatingpoint.html](https://docs.python.org/3.6/tutorial/floatingpoint.html)

### Complex Number

> &lt; class 'complex' &gt;

The fullfill of number system that add imaginary part to real number system. This Complex number can solve the problem which a value in squrt root is less than 0.

In Python, we can define complex number as 

**&lt;real part&gt; + &lt;imaginary part&gt; j**

for example,

{% code-tabs %}
{% code-tabs-item title="Complex Number" %}
```python
print(2+1j)
print(1992+26j)
print(13+37j)
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="OUTPUT" %}
```bash
(2+1j)
(1992+26j)
(13+37j)
```
{% endcode-tabs-item %}
{% endcode-tabs %}

### Strings

> &lt; class 'str' &gt;

String is the powerful datatype that I would like to introduce to all of you especially, in Python we have so many useful built-in functions to handle with string.

{% hint style="success" %}
Syntax

"Single quote" and "Double quote" are notation of String in Python

'AdaBrain'  and "AdaBrain" are the same.
{% endhint %}

for example,

{% code-tabs %}
{% code-tabs-item title="String" %}
```python
print('AdaBrain')
print("How are you?")
print("I'm studying a programming language")
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="OUTPUT" %}
```bash
AdaBrain
How are you?
I'm studying a programming language
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% hint style="success" %}
Triple-Quoted String

 ' ' 'abcde' ' '  
or  
" " " abcde " " "  
This syntax is allow you to do multiline strings
{% endhint %}

{% code-tabs %}
{% code-tabs-item title="Triple\_quoted" %}
```python
print('''Hello, how are you? 
Where are you going? 
Do like pop music?
''')
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="OUTPUT" %}
```bash
Hello, how are you? 
Where are you going? 
Do like pop music?
```
{% endcode-tabs-item %}
{% endcode-tabs %}

As I mention to you that Python has so many useful built-in functions to manipulate strings so I decide to seperate it to a chapter that you will see further.

### Boolean

> &lt; class 'bool' &gt;

Boolean is a datatype that really important to every programming I dare to say that "No Boolean, No Programming" because you can not control or program anything in advance.

{% hint style="success" %}
Syntax

**True** and **False**
{% endhint %}

for example,

{% code-tabs %}
{% code-tabs-item title="Boolean" %}
```python
print(True)
print(False)
```
{% endcode-tabs-item %}
{% endcode-tabs %}

{% code-tabs %}
{% code-tabs-item title="OUTPUT" %}
```bash
True
False
```
{% endcode-tabs-item %}
{% endcode-tabs %}

Boolean is useful in control logic thus in the next part of this course boolean will be our close friend.

In the next chapter, I will introduce you how to operate variable data in python. See you soon!

