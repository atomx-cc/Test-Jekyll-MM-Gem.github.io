---
title: "Mathematical Thinking Stanford, W2 Assignment 4"
date: 2023-9-25
categories:
  - IT
tags:
  - Internet
  - Math & CS
  - AI
---

# 1. Building truth table φ ⇔ ψ

| φ  | ψ | φ ⇒ ψ | ψ ⇒ φ | φ ⇔ ψ |
| --- | --- | --- | --- | --- |
| T | T | T | T | ✔︎ |
| T | F | F | T |  |
| F | T | T | F |  |
| F | F | T | T | ✔︎ |

a. φ ⇔ ψ is true if φ and ψ are both true or both false
(φ ⇒ ψ)=(ψ ⇒ φ) , (φ ⇒ ψ)∧(ψ ⇒ φ) = φ ⇔ ψ, φ = ψ

b. φ ⇔ ψ is false if exactly one of φ, ψ is true and the other false.

# 2. **Truth table (φ ⇒ ψ) ⇔ (¬φ ∨ ψ)**

| φ  | ψ | φ ⇒ ψ | ¬φ  | ¬φ  ∨ ψ |
| --- | --- | --- | --- | --- |
| T | T | T | F | T |
| T | F | F | F | F |
| F | T | T | T | T |
| F | F | T | T | T |

# 3. **Truth table (φ** ⇏ **ψ) ⇔ (φ** ∧ **¬ψ) tautology.**

| φ  | ψ | φ ⇏ ψ | **¬ψ** | **φ ∧ ¬ψ** |
| --- | --- | --- | --- | --- |
| T | T | F | F | F |
| T | F | T | T | T |
| F | T | F | F | F |
| F | F | F | T | F |

# 4. modus ponens

### A. [φ ∧ (φ ⇒ ψ)] ⇒ ψ

| φ  | ψ | φ ⇒ ψ | [φ ∧ (φ ⇒ ψ)]  | [φ ∧ (φ ⇒ ψ)] ⇒ ψ
 |
| --- | --- | --- | --- | --- |
| T | T | T | T | T |
| T | F | F | F | T |
| F | T | T | F | T |
| F | F | T | F | T |

### b. explain modus ponens

[φ ∧ (φ ⇒ ψ)] ⇒ ψ are all TRUE.

modus ponens: if you know φ and you know φ ⇒ ψ, then you can conclude ψ.

# 5. Prove Equivalence

by means of a logical argument, in natural language, we can deduce that

## ¬(φ∧ψ) **⇔** (¬φ)∨(¬ψ)

1. (φ∧ψ) , both φ and ψ are true
2. ¬(φ∧ψ) , not the case that both φ and ψ are true
3. If they are not both true, then at least one of φ or ψ must be false
4. the same as saying that, at least one of ¬φ or ¬ψ is true
5. (¬φ)∨(¬ψ)

4. This is clearly the same as saying that at least one of ¬φ **and** ¬ψ is true. (By the definition of negation).
here is an error, please change “and” to “or”

 

## ¬(φ∨ψ) **⇔** (¬φ)∧(¬ψ)

1. (φ∨ψ) , if either φ or ψ is true, then it is true.
2. ¬(φ∨ψ) , not the case that either φ or ψ is true.
3. if they are both false, then neither φ nor ψ is true, 
4. the same as saying that, both ¬φ and ¬ψ are true
5. (¬φ)∧(¬ψ)

# 6. Denial statement

(a) 34,159 is (a composite number) not a prime number.

(b) Roses are not red or violets are not blue.

(c) If there are no hamburgers, I will have a hot dog.

 ¬(φ ⇒ ψ) = φ ∧ ¬ ψ,  “∧ conjunction  uses but / and”

If there are no hamburgers, **but** I **won’t** have a hot dog.

(d) Fred will go but he will not play. 

this sentence is interpreted as (φ ∧ ¬ ψ)

the denial statement as ¬(φ ∧ ¬ ψ) 
**1. ¬(φ ∧ ¬ ψ) ⇔ (φ ⇒ ψ),** 

1.1 if Fred will go, then he will play. 

1.2 Fred will go, only if he will play.

1.3 Fred will play if he will go.

1.4 Fred will play whenever he will go.

1. ¬(φ ∧ ¬ ψ) ⇔ ¬ φ ∨ ψ 

2.1 Fred will not go or he will play.

¬(φ ∨ ψ )  ⇔ ¬ φ ∧ ¬ψ 

¬(φ ∧ ψ )  ⇔ ¬ φ ∨ ¬ψ 

(e) The number x is either negative or greater than 10.

(x<0)∨(x>10) either or 两者任一 disjunction ∨.  

¬ [(x<0)∨(x>10)] = (x≥0)∧(x≤10) = 0≤ x ≤10
 The number x is non-negative and less than or equal to 10. 

(f) We will win the first game or the second.

We will lose the first two games.

# 7. Show that φ ⇔ ψ = (¬φ) ⇔ (¬ψ).

| φ  | φ ⇔ ψ | ψ | ¬ φ  | ¬ψ | (¬φ) ⇔ (¬ψ) |
| --- | --- | --- | --- | --- | --- |
| T | T | T | F | F | T |
| T | T | T | F | F | T |
| F | T | F | T | T | T |
| F | T | F | T | T | T |

# 8. truth tables

### (a) φ ⇔ ψ

| φ  | φ ⇔ ψ | ψ |
| --- | --- | --- |
| T | T | T |
| T | T | T |
| F | T | F |
| F | T | F |

### (b) φ⇒(ψ∨θ)

| φ  | ψ | ψ∨θ | φ⇒(ψ∨θ) |
| --- | --- | --- | --- |
| T | T | T | T |
| T | F | T | T |
| F | T | T | T |
| F | F | F | T |

# 9. [φ ⇒ (ψ ∧ θ)] ⇔ [(φ ⇒ ψ) ∧ (φ ⇒ θ)]

| φ  | ψ | θ | ψ∧θ | **φ⇒(ψ∧θ)** | φ ⇒ ψ | φ ⇒ θ | **(φ ⇒ ψ) ∧ (φ ⇒ θ)** |
| --- | --- | --- | --- | --- | --- | --- | --- |
| T | T | T | T | T | T | T | **T** |
| T | F | F | F | F | F | F | **F** |
| F | T | F | F | T | T | T | **T** |
| F | F | T | F | T | T | T | **T** |

# 10. Verify the equivalence of previous

by means of a logical argument, in natural language, we can deduce that

**[φ ⇒ (ψ ∧ θ)] and [(φ ⇒ ψ) ∧ (φ ⇒ θ)]**

1. φ ⇒ (ψ ∧ θ)
2. ψ and θ from φ
3. ψ from φ, and θ  from φ
4. (φ ⇒ ψ) and (φ ⇒ θ)

 4. (φ ⇒ ψ) ∧ (φ ⇒ θ)

1. [φ ⇒ (ψ ∧ θ)] ⇔ [(φ ⇒ ψ) ∧ (φ ⇒ θ)]

**c. (φ** ∨ **ψ )⇒ θ and (φ ⇒ θ) ∧ (ψ ⇒ θ)**

1. φ ∨ ψ ⇒ θ
2.  ****θ from φ or ψ 
3.  ****θ from φ or  ****θ from ψ 
4. φ ⇒ θ or ψ ⇒ θ
5. (φ ⇒ θ) ∧ (ψ ⇒ θ)
6. [(φ ∨ ψ )⇒ θ] ⇔ [(φ ⇒ θ) ∧ (ψ ⇒ θ)]

 **c0. (φ ⇒ θ) ∧ (ψ ⇒ θ)  and (φ** ∨ **ψ )⇒ θ**

1. (φ ⇒ θ) ∧ (ψ ⇒ θ)  
2. θ from φ or  ****θ from ψ 
3. θ from φ or ψ 
4. (φ ∨ ψ )⇒ θ
5. [ (φ ⇒ θ) ∧ (ψ ⇒ θ)] ⇔  [(φ ∨ ψ )⇒ θ]

# 11. [φ ⇒ ψ] ⇔ [(¬ψ) ⇒ (¬φ)]

| φ  | ψ | **φ ⇒ ψ** | ¬ψ | ¬φ | **(¬ψ) ⇒ (¬φ)** |
| --- | --- | --- | --- | --- | --- |
| T | T | **T** | F | F | **T** |
| T | F | **F** | T | F | **F** |
| F | T | **T** | F | T | **T** |
| F | F | **T** | T | T | **T** |

(¬ψ) ⇒ (¬φ) is **Contrapositives** of φ ⇒ ψ.

# 12. Contrapositives of the statements

(a) rectangles congruent ⇒ same area
**Contrapositives:** 

¬ same area ⇒ ¬ rectangles congruent
 If two rectangles don’t have the same area, they are not congruent.

**(b)** If a triangle with sides a, b, c (c largest) is right-angled, then  $a^2 + b^2$ = $c^2$

**Contrapositives:** 

1. right-angled ⇒  $a^2 + b^2$ = $c^2$
2. ¬ ( $a^2 + b^2$ = $c^2$ ) ⇒ ¬  right-angled 

If a triangle with sides a, b, c (c largest) and  $a^2 + b^2$ ≠ $c^2$, then it is not right-angled.

(c) ( $2^n$ − 1) prime ⇒ $n$ prime

**Contrapositives:**   

¬ $n$ prime ⇒ ¬ ( $2^n$ − 1) prime 

If  $n$ is not prime, then $2^n$ − 1 is not prime.

(d) Yuan rise ⇒ Dollar fall

**Contrapositives:**  

 ¬ Dollar fall ⇒ ¬ Yuan rise

If the Dollar not fall, the Yuan will not rises.

# 13. Converse [φ ⇒ ψ] ⇎ [ψ ⇒ φ]

| φ  | ψ | **φ ⇒ ψ** | **ψ ⇒ φ** |
| --- | --- | --- | --- |
| T | T | **T** | **T** |
| T | F | **F** | **T** |
| F | T | **T** | **F** |
| F | F | **T** | **T** |

Don’t confuse the contrapositive and converse

# 14. Converses of the statements 12

(a) rectangles congruent ⇒ same area
**Converses:** rectangles same area ⇒ congruent
 If two rectangles have the same area, they are congruent. F

(b) triangle ⇒  $a^2 + b^2$ = $c^2$
**Converses:** ( $a^2 + b^2$ = $c^2$ ) ⇒ triangle 
If a triangle with sides a, b, c (c largest) and  $a^2 + b^2$ = $c^2$, then it is a right-angled. T

(c) ( $2^n$ − 1) prime ⇒ $n$ prime

**Converses:** $n$ prime ⇒ ( $2^n$ − 1) prime 

If  $n$ is prime, then $2^n$ − 1 is prime.

(d) Yuan rise ⇒ Dollar fall

**Converses:** Dollar fall ⇒ Yuan rise

If the Dollar fall, the Yuan will rises.

# OPTIONAL PROBLEMS

## 1. Express the combinator

φ unless ψ

## 2  ∨ ̇  exclusive or

either one or the other but not both

| φ  | ψ |  |  |
| --- | --- | --- | --- |
| T | T |  |  |
| T | F |  |  |
| F | T |  |  |
| F | F |  |  |

## 3. Express φ ∨ ̇ ψ in terms of the basic combinators ∧, ∨, ¬.

## 4. true conditional sentence

the converse

| φ  | ψ | φ ⇒ ψ | **ψ ⇒ φ** |
| --- | --- | --- | --- |
| F | T | T | **F** |
| F | F | T | **T** |

Contrapositives

| φ  | ψ | φ ⇒ ψ | ¬ψ | ¬φ | **(¬ψ) ⇒ (¬φ)** |
| --- | --- | --- | --- | --- | --- |
| T | T | T | F | F | **T** |
| T | F | **F** | T | F | **F** |

## 5. Mod-2 arithmetic

| M | N | M x N | M+N |
| --- | --- | --- | --- |
| 1 | 1 |  | 0 |
| 1 | 0 |  | 0 |
| 0 | 1 |  | 1 |
| 0 | 0 | ? | 0 |

# 6. denoting statements

interpret 1 as T and 0 as F

| M | N | M x N | M+N |
| --- | --- | --- | --- |
| T | T |  | F |
| T | F |  |  |
| F | T |  |  |
| F | F |  |  |

(a) ∧, ∨ corresponds to × ?

(b) ∧, ∨ corresponds to + ?

(c) Does ¬ correspond to − (minus)?

# 7. denoting statements

interpret 0 as T and 1 as F

| M | N | M x N | M+N |
| --- | --- | --- | --- |
| F | F |  | T |
| F | T |  | T |
| T | F |  | F |
| T | T |  | T |

(a) ∧, ∨ corresponds to × ?

(b) + correspond to ⇒

# 8 Card puzzle

B, E, 4, 7

at least 3 cards as follows:

A, I, O, U

1, 3, 5, 9,

# 9. Prove that mn is odd iff m and n are odd.

⇔ iff = if only if = equivalence totally, double direction 

mn is odd ⇔  m and n are odd

mn= 15, m=3, n=5

mn= 39, m=3, n=13

True

# 10.  Prove that mn is even iff m and n are even

~~mn is even ⇔  m and n are even~~

mn=6, m=2, n=3

False

# 11. Party

check  beer(alcohol) holder’s IDs

# 12. Compare the logical structure

soft drinks are safe that everybody could take, so just only check the most crucial one is easier.