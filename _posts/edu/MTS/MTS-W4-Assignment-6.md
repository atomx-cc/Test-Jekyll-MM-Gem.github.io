---
title: "Mathematical Thinking Stanford, W4 Assignment 6"
date: 2023-9- 00 
categories:
  - IT
tags:
  - Internet
  - Math & CS
  - AI
---

1. ¬ [$∃x$A(x)] = $∀x$[¬A(x)] ?

¬ [$∃x$A(x)]

if it is not the case that at least a x satisfies A(x), 

then for all x are not not satisfy A(x),

so for all x, ¬A(x) is true.

$∀x$[¬A(x)] 

2. Prove false

*There is an even prime bigger than 2*

x are parts of natural number set $N$, Prime number P(x), Even number E(x)

$∃x$[E(x)P(x)∧(x>2)]

¬ {$∃x$[E(x)P(x)∧(x>2)]} is True

$∀x$[E(x)P(x) ⇒ (2≥ x)]

As we known when 2≥ x, the all prime numbers are even. because the only is 2. 

so this statement is true.

in other word, it means 

$∃x$[E(x)P(x)∧(x>2)] is false.

**De Morgan’s Law**

¬(φ ∨ ψ )  ⇔ ¬ φ ∧ ¬ψ 

¬(φ ∧ ψ )  ⇔ ¬ φ ∨ ¬ψ 

$¬ ∃x$E(x)P(x) ∨ $¬ ∃x$E(x)(x>2)

$¬ ∃x$E(x)P(x) ∨ $¬ ∃x$E(x)(x≤2)

# 3.  symbolic form

(a) All students like pizza. (All people)
$∀x$ P$(x)$ (x∈ People), P(x) people like Pizza.

(b) One of my friends does not have a car. (All people)
$∀x$$∃y$[(x= y ) ⇒ ¬ D(x)]
(x∈ People), D(x) people like car, one of my friend y

(c) Some elephants do not like muffins. (All animals)
$∀x$$∃x${(x=e) ∧ ¬ M(x)}
(x∈ All animals), M(x) animals like muffins, Elephants e.

(d) Every triangle is isosceles. (All geometric figures)

x is the set of all geometric figures, Triangle t, isosceles are G(i)
$∀x$ $∀t$ [(x=t) ⇒ G(i)]

(e) Some of the students in the class are not here today.

Students x, at here T(x)
$∀x$$∃x$ ∧ ¬ T(x)

(f) Everyone loves somebody. (All people)

x People, Love L(x)
$∀x$L(x)$∃x$

(g) Nobody loves everybody. (All people)

$¬ ∃x$ L(x) ∀x

(h) If a man comes, all the women will leave. (All people)

C(m), L(w)

$∀x$$∃x$ [C(m) ⇒ L(w)]

(i) All people are tall or short. (All people)

People x, tall T(x), short S(x)

$∀x$[T(x) ∨ S(x)]

(j) All people are tall or all people are short. (All people)

$∀x$T(x) ∨ $∀x$S(x)

(k) Not all precious stones are beautiful. (All stones)

Stones x, P(x), B(x)

¬ [$∀x$P(x)∧ B(x)]

¬{¬ [$∀x$P(x)∧ B(x)]}

$∀x$P(x)∧ B(x)

All precious stones are beautiful

(l) Nobody loves me. (All people) 

L(x) people love someone

$∀x$ [¬ L(x)]$∃x$[(x= me) ]

¬ { $∀x$ [¬ L(x)]$∃x$[(x= me) ] }

$∀x$ L(x) $∃x$[(x= me) 

All people love me

(m) At least one American snake is poisonous. (All snakes)

S snakes, 

$∀x$ (x ∈ S) $∃x$[ A(x) ∧ P(x)]

¬ { $∀x$ (x ∈ S) $∃x$[ A(x) ∧ P(x)] }

(n) At least one American snake is poisonous. (All animals)

S snakes, x animals

$∀x$ (x ∈ A) $∃x$[A(x)(x=s) ⇒ P(x)]

# 5. True

b, c, d, 

# 7. Negate the following statements

(a) (∀x∈N)(∃y∈N)(x+y=1)

¬ { (∀x∈N)(∃y∈N)(x+y=1) }

($∃x$∈N)($∀y$∈N)(x+y ≠ 1)

(b) (∀x > 0)(∃y < 0)(x + y = 0) (where x, y are real number variables)
¬ { (∀x > 0)(∃y < 0)(x + y = 0) }

($∃x$ > 0)($∀y$ ≥ 0)(x + y ≠ 0)

(c) ∃x(∀ε > 0)(−ε < x < ε) (where x, ε are real number variables)

¬ { ∃x(∀ε > 0)(−ε < x < ε) }

$∀x$ ( $∃ε$> 0)[(−ε ≥ x) ∨ (x ≥ ε)]

(d) (∀x∈N)(∀y∈N)(∃z∈N)(x+y=$z^2$)

¬ { (∀x∈N)(∀y∈N)(∃z∈N)(x+y=z2) }

($∃x$∈N)($∃y$∈N)($∀z$∈N)(x+y ≠ $z^2$)

# 8. Abraham Lincoln sentence negation

People p, Fool F(p,t), Time t 

$∃t$$∀p$ F$(p,t)$  ∧ $∃p$$∀t$ F$(p,t)$  ∧ ¬[$∀p$ $∀t$ F$(p,t)$ ]

¬ { }

$∃p$$∀t$¬ F$(p,t)$  ∨ $∃t$$∀p$ ¬F$(p,t)$  ∨ $∀p$$∀t$F$(p,t)$ 

You can not fool some of the people all the time, 

or you can not fool all of the people sometime.

or you can fool all of the people all the time.

# 9. Negation of a function

(∀ε > 0)(∃δ > 0)(∀x)[|x − a| < δ ⇒ |f(x) − f(a)| < ε]

¬ { (∀ε > 0)(∃δ > 0)(∀x)[|x − a| < δ ⇒ |f(x) − f(a)| < ε] }

($∃ε$ > 0)($∀δ$ > 0)($∃x$)[|x − a| < δ ∧ |f(x) − f(a)| ≥ ε]

implication law

¬(φ ⇒ ψ)  ⇔  φ ∧ ¬ψ

φ ⇒ ψ  ⇔  ¬φ ∨ ψ

# Quiz - Problem set

1. (b) $∀p∀q∃t$W$(p,q,t)$, False

people p, q, tennis game t, p wins q in a game.

interpret, everyone could win everyone in some games, for  $∀p∀q$, it means  p=q, including all people, people can not beat themselves in a game.

so it is False.

1. Euclid’s proof of the infinitude of the primes.

If integer N is divisible by a Prime P, then N+1 is not be divisible by P.

integer N, Prime P, integer Q

N = PQ

Assume N+1 could be divisible by P, get integer R

N+1 = PR

1= PR- PQ

1=P(R-Q)

Both R and Q are integers, so it is impossible to get 1 in this equation, so the assume is False.