---
title: "Mathematical Thinking Stanford, W7"
date: 2023-9- 00 
categories:
  - IT
tags:
  - Internet
  - Math & CS
  - AI
---

# number theory

[Number theory | Definition, Topics, & History | Britannica](https://www.britannica.com/science/number-theory)

0 is not a natural number? it depends on the mathematical community, if they design the norm(standard) that 0 i a natural number, then it is. 

but in a default condition, we normally set 0 is not natural number.

## b|a

Vertical bar sign in Discrete mathematics, means b divides a, b is a *factor* of a.

division theory ?

[Euclidean division - Wikipedia](https://en.wikipedia.org/wiki/Euclidean_division)

overkill 矫枉过正

# Assignment9

1. Express as concisely and accurately as you can the relationship between b|a and a/b.

a/b is a notion that denotes the rational number a divided by b.

b|a denotes the relation that **b divides a**, i.e, there is an integers q such that a=bq.

thus b|a only if a/b is an integer, b≠0, a>b, |q|>|r| 

1. prove your answer

(a) 0|7, False, a|b includes the requirement a≠0

(b) 9|0, true, 0=0x9, so $∃q$[0=q.9] 

(c) 0|0, False, the same as (a)

(d) 1|1, true, 1=1x1, so $∃q$[1=q.1] 
(e) 7|44, false, ¬$∃q$[44=q.7] 

(f) 7|(−42), true, $∃q$[-42= q.7] 

(g) (−7)|49, true, $∃q$[49= q.-7] 

(h) (−7)|(−56), true, $∃q$[-56= q.-7] 
(i) ($∀n$ ∈ Z)[1|n], true, for $∀n$ ∈ Z, $∃q$[n= q.1] 

(j) ($∀n$ ∈ N )[n|0], true, for $∀n$ ∈ N(n≠0), $∃q$[0= q.n] 

(k) ($∀n$ ∈ Z)[n|0], false, because , (n=0)∈ Z

1. Prove all the parts of the theorem

(a) a|0, a|a ;  true
(b) a|1 if and only if a = ±1 ; prove: 1= qa =  |q.a|=|q|.|a|, so |q|=|a|=1
(c) if a|b and c|d, then ac|bd (for c ≠ 0) ; true
(d) if a|b and b|c, then a|c (for b ≠ 0) ; true
(e) [a|b and b|a] if and only if a = ±b ; true
(f) if a|b and b ≠ 0, then |a| ≤ |b| ; true
(g) if a|b and a|c, then a|(bx + cy) for any integers x, y.