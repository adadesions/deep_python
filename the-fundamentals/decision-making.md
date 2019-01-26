---
description: >-
  Without a logical thinking we can't create such an intelligent machine or even
  decide to work.
---

# Decision Making

## IF-ELSE Statement

In Python, it's no difference from other languages likes C/C++, Javascript, or R. Especially,  the concept of control-flow now I'm willing to introduce you to if-else statament the powerful thing that you can't miss**.**

{% hint style="success" %}
**Syntax**

**if &lt;conditions&gt; :**  
    \#do something  
**elif &lt;conditions&gt; :**  
    \#do something  
**else:**  
   \# do something
{% endhint %}

If you want to write some program that contains with decision making you should apply IF-ELSE statament in your code. Let's see examples!

### Example 

**1.I would like to know that a number I was received from user is an even or odd number. How to know that?**  
  
**solution**  
You have to know the definition of an even and odd number whether,  Even number is a number evenly divisible by 2 and an odd in the opposite way.

{% code-tabs %}
{% code-tabs-item title="is\_even.py" %}
```python
num = 12
if num%2 == 0:
    print('{} is an even number.'.format(num))
else:
    print('{} is an odd number.'.format(num))
    
================================================================================
OUTPUT:
12 is an even number.
```
{% endcode-tabs-item %}
{% endcode-tabs %}

**2. Write a program to determine the discriminant of quadratic polynomial.**

**if the discriminant is** $$D = b^2-4ac =  \left\{ \begin{array}{ll}      1 & root & D = 0 \\      2 & roots &  D\gt 0 \\       No & root & D\lt 0 \\ \end{array}  \right.$$ 

**solution**

{% code-tabs %}
{% code-tabs-item title="discriminant.py" %}
```python
a, b, c = 1, 4, 2
D = b**2 - 4*a*c

if D == 0:
    print('Has one root')
elif D > 0:
    print('Has two roots')
else:
    print('Has no root')

================================================================================
OUTPUT:
Has two roots
```
{% endcode-tabs-item %}
{% endcode-tabs %}

I hope you love this concept because it's very useful and much know to programming in higher level. See you next chapter!



