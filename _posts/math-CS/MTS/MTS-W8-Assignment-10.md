---
title: "Mathematical Thinking Stanford, W8 Assignment 10"
date: 2023-9- 00 
categories:
  - IT
tags:
  - Internet
  - Math & CS
  - AI
---

cognitive conception

completeness property 完整属性

[upper and lower bound](https://en.wikipedia.org/wiki/Upper_and_lower_bounds) 上界、下界

[least upper bound](https://en.wikipedia.org/wiki/Least-upper-bound_property) 最小上界 LUB

S[et theory](https://en.wikipedia.org/wiki/Set_(mathematics))

**subset relations**

Natural numbers, Integers, Rational numbers, Real numbers

N ⊂ Z ⊂ Q ⊂ R 

[Elements of Set Theory](https://d3c33hcgiwev3.cloudfront.net/_1dc41c143a819b67c9704cc09941d38c_Supplement__Set_Theory_.pdf?Expires=1697241600&Signature=lfPfw5Vn7fiAaHasCEMQXvvrAJXuC0gXdHIGZQbE6xCRPvbJqZ0yqwjR5AJttYA~AFZP8xcRYp1xsDqJOy4bZIqgM4dn76VEDOpsG4JmtHK1ZnLSyRJDjFEibvQk1ux8H7Yzdhl0rj6Bd--vmOv3FLqz5ZCwlC-p3wGxvuAJdko_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)(SUPPLEMENT, KEITH DEVLIN: Introduction to Mathematical Thinking)

empty set ∅

different from  **Φ(phi)** [the 21st letter of the Greek alphabet](https://en.wikipedia.org/wiki/Phi)

eg. **Set A**

If $A(x)$ is some property, the set of all those x which satisfy $A(x)$ is denoted by {$x | A(x)$}

**Union of A and B**

A ∪ B = {x | (x ∈ A) ∨ (x ∈ B)}

the set of all objects which are members of either one of A and B.

**The intersection of the sets A, B**

A ∩ B = {x | (x ∈ A) ∧ (x ∈ B)}

the set of all members which A and B have in common.

**Complement of the set A**

the universal set U

$𝐴^′$   = {$x$ ∈ U | $x$ ∉ A}

## [Venn diagrams](https://en.wikipedia.org/wiki/Venn_diagram)

 illustrate the below theorem.

**the associative laws**

(1) $A ∪ (B ∪ C) = (A ∪ B) ∪ C$  
(2) $A ∩ (B ∩ C) = (A ∩ B) ∩ C$  
结合律

**commutative laws**

(3) $A ∪ B = B ∪ A$  
(4) $A ∩ B = B ∩ A$  
交换律

**the distributive laws**

(5) $A ∪ (B ∩ C) = (A ∪ B) ∩ (A ∪ C)$  
(6) $A ∩ (B ∪ C) = (A ∩ B) ∪ (A ∩ C)$  
分配律

**the De Morgan laws**

(7) $(A∪B)^′$  = $A^′∩ B^′$  
(8)  $(A∩B)^′$   = $A^′∪ B^′$

**the complementation laws**  
(9)  $A ∪ A^′$  = U  
(10) $A ∩ A^′$  = ∅  
互补律

**self-inverse law**
(11) $（A^′）^′$ = $A$  
自逆律

### Beginning of “real analysis”

Lecture 10B - Real Analysis 2

**Theorem: the rational line is not complete.**

Proof: let A={r∈ Q | r≥0 ∧ $r^2$<2 }

? 

As n gets larger

$\frac{n^2}{2n+1}$

$\frac{n^2}{2n+1}\ >\ \frac{p2}{2q^2\ -\ p^2}$

### Real number sequences

the number get close to a limit.

$\left\{\frac{1}{n}\right\}_{\left(n=1\right)}^∞$ = {1, $1/2, 1/3,$ …… }, the number arbitrarily get closer to 0 

alternatively sequence

$\left\{\left(-1\right)^{\left(n+1\right)}\right\}_{\left(n=1\right)}^∞$= {1, -1, 1, -1, …… }

geometric intuition 几何直觉

( Ε, ε )epsilon, the fifth letter of the Greek alphabet. 

# ASSIGNMENT 10.1 (for Lecture 10A)

## 1. interval intersection

set there are open intervals (a,b),(c,d), a<c<b<d

**so (c,b) is another interval (why not write in this form?)**

that (a,c)<(c,b)<(b,d)

this is the same true to closed interval.

it is not the same true for unions, because they don’t have intersection.

⊔, ⊓

let  A=(a,b), C=(c,d)

A⊓C = {x| a<x<b } ⊓ {x| c<x<d }

= {x| max(a,c) <x< min(b,d)}

= (max(a,c), min(b,d))

similarly for closed and half-open intervals

it is false for unions, eg. (0,1)⊔(4,5) is not an interval.

1. express in intervals or unions of intervals

## 5. Let A be a set of integers, rationals, or reals. Prove that b is the least upper bound of A iff:

(a) ($∀a$ ∈ A)(a ≤ b); and
(b) whenever c < b there is an a ∈ A such that a > c.

**Prove:**

(a) says b is an upper bound of A.

b is a LUB iff **no c<b is an upper bound.(*? что Ето)**

iff, for any c<b, c is not an upper bound.

iff, for any c<b, there is an $a∈A$ such that ¬(a≤c).

iff, for any c<b, there is an $a∈A$ such that c<a.

c<a≤b

## 6.The following variant of the above characterization is often found. Show that b is the lub of A iff:

(a) ($∀a$ ∈ A)(a ≤ b) ; and
(b) ($∀e$ > 0)($∃a$ ∈ A)($a>b−e$ )

**Prove:**

(a) says b is an upper bound of A.

a ≤ b

a > b − e

$e$ > 0

## 8. Show that any finite set of integers/rationals/reals has a least upper bound.

(a<10), a∈Z , iff LUB = 9

(a<10), a∈Q, LUB = b, iff b∈Q, a<b<10 

(a<10), a∈R,  LUB = b, iff b∈Q, a<b<10 

## 11. Define the notion of a lower bound of a set of integers/rationals/reals.

**a lower bound**

(a>0), a∈Z , LB = b, iff b∈Z, 0<b≤a, b=1

(a>0), a∈Q, LB = b, iff b∈Q, 0<b≤a 

(a>0), a∈R,  LB = b, iff b∈R, 0<b≤a

# ASSIGNMENT 10.2 (for Lecture 10C)

[Archimedean property](https://en.wikipedia.org/wiki/Archimedean_property)

1. A = {r ∈ Q | r > 0 ∧ $r^2$ > 3}. 
translate it as : 

A = {r ∈ Q | r > 0 ∧ [$r$< -$\sqrt{3}$)V($r$ > $\sqrt{3}$)] }

A = {r ∈ Q | $r$ > $\sqrt{3}$ }

A = {r ∈ Q | ( $\sqrt{3}$, ∞ )}

A has a lower bound in Q, LB= $\sqrt{3}$

but no greatest lower bound and upper bound.

## 4. Prove that $(\frac{n}{n+1})^2$ → 1 as n → ∞.

give 𝜀>0, we seek an integer N s.t.(such that) 

n≥ N  ⇒ | $(\frac{n}{n+1})^2$-1 | < 𝜀

i.e, s.t. n≥ N  ⇒ | $\frac{n^2-n^2-2n-1}{\left(n+1\right)^2}$  | < 𝜀

i.e, s.t. n≥ N  ⇒ $\frac{2n+1}{\left(n+1\right)^2}$  < 𝜀

Pick N so big, that $\frac{\left(n+1\right)^2} {2n+1}$ ≥ $\frac{\left(N+1\right)^2} {2N+1}$ > 𝜀 

then,  n≥ N  ⇒ $\frac{2n+1}{\left(n+1\right)^2}$  ≤ $\frac{2N+1}{\left(N+1\right)^2}$ < 𝜀

so, n≥ N  ⇒ | $(\frac{n}{n+1})^2$-1 | < 𝜀

