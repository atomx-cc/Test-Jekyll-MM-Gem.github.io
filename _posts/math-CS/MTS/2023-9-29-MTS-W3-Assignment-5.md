---
title: "Mathematical Thinking Stanford, W3 Assignment 5"
date: 2023-9-29
categories:
  - IT
tags:
  - Internet
  - Math & CS
  - AI
---


(∀𝑚∈ ℕ)(∃𝑛 ∈ ℕ)(𝑛>𝑚), True 

1. Express the existence assertions

a. ($∃x$ ∈ ℕ)($x^3 = 27$ )

b. ($∃𝑛$ ∈ ℕ)(𝑛>10000)

c. natural number n is not a prime
($∃p$ ∈ ℕ)($∃m$ ∈ ℕ)($p$>1 **∧** $m$>1 **∧ $n=pm$**)

1. Express the ‘for all’ assertions

a. ($∀x$ ∉ ℕ)($x^3$ = 28)
 ¬($∃x$ ∈ $ℕ$)($x^3$ = 28)
($∀x$ ∈ ℕ)($x^3$ ≠ 28)

($∀x$ ∈ ℕ)¬($x^3$ = 28)

b. ($∀n$ ∈ ℕ)($n>0$ )
c.  ($∀p$ ∈ ℕ)($∀q$ ∈ ℕ)[( ****$n=pq$) ****⇒**$n=pq**n=pq$$p$=1 V **$q=1$** )]

1. quantifiers for people

a. ($∀x$)($∃y$) $L(x,y)$, where $L(x,y)$ denotes “$x$ love $y$” 

b. ($∀x$) [Tall$(x)$ V Short$(x)$]

c. [($∀x$) Tall$(x)$] V [($∀x)$ Short$(x)$]

d. ($∀n$)[¬ At-home$(n)$]
($¬∃n$)[At-home$(n)$]

e. if  John comes, all the women will leave.
Come$(John)$  ⇒ $∀x$[Woman$(x)$ ⇒Leave$(x)$]

f. if a man comes, all the women will leave.
($∃x$)[Man$(x)$ **∧** Comes$(x)$] ⇒ ($∀x$)[Woman$(x)$⇒Leave$(x)$]

1. Express quantifiers

a. the equation $x^2$ + a = 0 has a real root **for** any real number a.
($x^2$ + a = 0) **∧** [($∃x$, $∀a$) ∈ $R$]? 

($∀a$ ∈ $R$)($∃x$∈ $R$)($x^2$ + a = 0)
Don’t mistake the order, “real number a” should be on first, then follows others, because **“x”** depends on “**a”**. otherwise, it will be wrong express, take “American Melanoma Foundation” for example.

b.  the equation $x^2$ + a = 0 has a real root **for** any negative real number a.
($∀a$∈R)[(a<0)⇒($∃x$∈R)($x^2$ + a = 0)]

c. Every real number is rational. (False statement)

($∀a$ ∈ $R$)($∃x$∈ $N$)($∃y$∈ $N$)(a=x/y V a=-x/y V a=0)

($∀a$ ∈ $R$)($∃x$∈ $Z$)($∃y$∈ $Z$)(a=x/y, V a=0)? is it a right solution?

R, [Real number](https://en.wikipedia.org/wiki/Real_number), 

Q, [Rational number](https://en.wikipedia.org/wiki/Rational_number),  x/y of two integers.

Z, [*Integer](https://en.wikipedia.org/wiki/Integer_(computer_science)) number(+, -)*

N, [Nature number](https://en.wikipedia.org/wiki/Natural_number), **non-negative integers** 0, 1, 2, 3, …… N

R>Q>Z>N, the order is from big to small number set.

d. there is an irrational number. 
($∃a$ ∈ $R$)($∀x$∈ $N$)($∀y$∈ $N$)(a≠x/y **∧**  a≠-x/y)

e. there is no largest rational number
{($∀i$, $∃ir$) ∈ $R$\$Q$}($i>ir$)?

($∀r$∈$R$)($∃p$∈$R$)[(p>r)**∧**($∀m$∈$N$)($∀n$∈$N$) (p≠m/n)]

For all real number r, there is an number p, when p is greater than r, and  for all nature number m and n, p is not equal to that m divided by n, so p is irrational number, it means that there is always an irrational number greater than a real number r.

1. Express in symbolic form

a. ($∀x$∈C)[D$(x)$ ⇒ M$(x)$]

b. ($∀x$∈C)[¬D(x) ⇒  M(x)]

c. ($∀x$∈C)[M(x) ⇒ D(x)], universal quantifier $∀x$, usually compare it with conditional implication ⇒

d. ($∃x$∈C)[D(x)**∧** ¬M(x)], existential quantifier $∃x$∈, typically compare it with conjunction **∧**

e. ($∃x$∈C)[¬D(x) **∧** M(x)]

1. You can find a rational number between any two unequal real number.

$∀x$ $∀y${(x<y) ⇒$∃z$ $∃z$ $Q(z)$ **∧**(x<z<y)]}

7. Abraham Lincoln : “You may fool all the people some of the time, you can even fool some of the people all of the time, but you cannot fool all of the people all the time.”

F$(p,t)$ = You may fool people p, at time t.

[F($∀p$ ∧ $∃t$) V ($∀t$ ∧ $∃p$)] **∧**[¬ Fool ($∀t$ ∧ $∀p$ )]

($∃t$$∀p$ ∧ $∃p$$∀t$ ∧ ¬$∀t$$∀p$)F$(p,t)$ ? is it a right solution?

$∃t$$∀p$F$(p,t)$  ∧ $∃p$$∀t$F$(p,t)$  ∧ ¬$∀t$$∀p$)F$(p,t)$ 

**Something =** $∃$

1. A driver is involved in an accident every six seconds. False statement, ambiguous

A(d, t) , Driver in d, an accident in a, every six seconds in t

$∃d$  $∀t$(t= every 6 seconds)A$(d,t)$

8.1 Every six seconds A driver is involved in an accident. True statement, precise.

$∀t$ $∃d$  A$(d,t)$

# Quiz

1. 
d. they win **exactly** a match when they are partners. $(∃!t)$ W(t)
f. If Rosario wins the match, she must be partnering with Antonio. 
the Scope is double tennis, it is not in this case that only Rosario. 

3. there is no largest prime.

$∀x$$∃y$ [Prime(x)∧Prime(y)∧(x<y)], 
$∀x$ $∀y$ [Prime(x)∧Prime(y)∧(x<y)], 

$∃y$ $∀x$[Prime(x)∧(y<x)], 
$∀x$ Prime(x) is False. Because there exist lots of Prime number x that is not greater than natural number y. so we can not set 
$∀x$ Prime(x) 

1. Evaluate this purported proof, according to the course rubric.

PS3_Q6.pdf
4+3+2+0+0+2 = 11 ? 

Teacher’s standard answer 4+0+0+4+0+2=10