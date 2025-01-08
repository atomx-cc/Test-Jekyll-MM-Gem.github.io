---
title: "Mathematical Thinking Stanford, W6 Assignment 8"
date: 2023-9- 00 
categories:
  - IT
tags:
  - Internet
  - Math & CS
  - AI
---

Induction: the inference of a general law from particular instances.

Axiom/ principle: generally acknowledged truth.

**to prove $∀n$ A$(n)$** 

Method, principle of mathematical induction

1. Prove **A$(1)$** 
2. Dominoes:  $∀n$ [ A$(n)$ ⇒ A$(n+1)$] induction step

**Theorem: for any n, 1+2+3 …… + n = 1/2n(n+1)**

if n = 1, both side equal to 1, then the identity is true.

Assume  A$(n)$ and deduce A$(n+1)$, the identity holds for all n

**1+2+3 …… + n+1 = 1/2(n+1)[(n+1)+1]**

**1/2(n+1)[(n+1)+1] = 1/2(n+1)(n+2)**

**1/2n(n+1) + (n+1) = 1/2(n+1)(n+2)**

so **1/2(n+1)[(n+1)+1] = 1/2n(n+1) + (n+1)**

so  **1+2+3 …… + n = 1/2n(n+1)**

hence, by the principle of mathematical induction, the identity holds for all n

# Assignment 8

## 1. Prove or disprove the claim that there are integers m, n such that $m^2$ +mn+$n^2$ is a perfect square.

(m, n)∈ $Z$ integer, perfect square 

if m=n,  then $m^2$ +mn+$n^2$ = 3$m^2$  = 3$n^2$, for any integers(m, n), because 3 root square is irrational, it is not a perfect square. 

if m≠ n, such as m=1, n=3, then $m^2$ +mn+$n^2$ = 1+3+9= 13, it is not perfect square, the statement is false. 

Assume $∀n$ [ A$(n)$ ⇒ A$(n+1)$] and  $∀m$ [ A$(m)$ ⇒ A$(m+1)$] 

 $(m+1)^2$ +(m+1)(n+1)+$(n+1)^2$

($m^2$ +2m+1)+ (mn+m+n+1) + ($n^2$+2n+1)

 ($m^2$ +mn+$n^2$) + 3(m+n+1)

if m=n,  then 3($m^2$ +2m+1)=3$(m+1)^2$, or 3$(n+1)^2$, because 3, it is not a perfect square. 

if m≠ n, Assume it is perfect square $x^2$, $y^2$ that

$m^2$ +mn+$n^2$ = $x^2$

($m^2$ +mn+$n^2$) + 3(m+n+1)= ?

$x^2$ + 3(m+n+1) 

because (m+n) = ($x^2$ - $n^2$)/$m$

$x^2$ +3 + 3($x^2$ - $n^2$)/$m$

 [m$x^2$ +3m + 3($x^2$ - $n^2$)]/$m$

[m$x^2$ +3m + 3$x^2$ - 3$n^2$]/$m$

$x^2$(m+3)+3(m-$n^2$)

 it is not perfect square, the statement is false. 

when m=n, $m^2$ +mn+$n^2$ is not perfect square. 

  $∀n$ [ A$(n)$ ⇒ A$(n+1)$] and  $∀m$ [ A$(m)$ ⇒ A$(m+1)$]  is false.

1. when m≠ n, assume $m^2$ +mn+$n^2$ is a perfect square, (x ≥ 1) )∈ $Z$ 

 $m^2$ +mn+$n^2$ = $(m+x)^2$ =  $m^2$ + 2mx+ $x^2$ 

mn+$n^2$ -2mx - $x^2$ = 0

when x=1, mn+$n^2$ -2mx - $x^2$ = mn+$n^2$-2m - 1 =  $n^2$-m(2-n) - 1

1. when m≠ n, assume $m^2$ +mn+$n^2$ is a perfect square, (x ≥ 1) )∈ $Z$ 

$m^2$ +mn+$n^2$ =  $x^2$ 

$(m+n)^2$ - mn =  $x^2$ 

Assume  $∀n$ [ A$(n)$ ⇒ A$(n+1)$] and  $∀m$ [ A$(m)$ ⇒ A$(m+1)$]  is True

then 

$(m+n+2)^2$ - (mn+m+n+1) =  ?

$(m+n)^2$+ 4(m+n)+ 4  - (mn+m+n+1) =  ?

[$(m+n)^2$ - mn ] + 3(m+n+1)=?

$x^2$ + 3(m+n+1)=?

please prove the equation. 

## 2. mn + 1 is a perfect square.

(m, n, x > 0)∈ $Z$ integer,  $∀m$$∃n$ [(mn + 1)  ] 

when m=1, n=3, 15, 24 (mn + 1) = 4, 16, 25, it is a perfect square.

set mn + 1 = $x^2$

mn= $x^2$ - 1 = (x+1)(x-1)

let m=x+1, n=x-1

mn + 1 = $(m-1)^2$, $m^2$ -2m - mn = 0, m -2 = n

mn + 1 = $(n+1)^2$

m(m-2) +1 = $(m -1)^2$

so, it is true.

## 3. $f(n) = n^2 + bn + c$

set (b, c, n, x, y > 0)∈ $Z$ 

if  $f(n)$  is composite number, then  $f(n)$  = (n+x)(n+y) 

x+y = b

xy = c

when x=1, y =2, b=3, c=2

$f(n)$  = (n+1)(n+2) 

## 4. Goldbach Conjecture

set ( k>1)∈ $Z$ , (p, q) ∈ P

when n∈Even,  n=2k > 2

when n∈Odd, n=2k+3 > 5

2k = p+q

n= p+q+3

here are 3 primes, so it is true.

## 5.  Σ n = $n^2$, n ∈ Odd

when n =3, Σ n = 1+3+5= 9 = $3^2$, it is true.

assume Σ n = $n^2$,  $∀n$ [ A$(n)$ ⇒ A$(n+1)$] 

Σ (n+1)  = $(n+1)^2$ 

the (n+1) th Odd number = 2n + 1

the (n) th Odd number = 2n - 1

Σ (n+1) = Σ n + (2n + 1) =  $n^2$+ 2n + 1 

so Σ (n+1)  = $(n+1)^2$ 

the statement is true

6.

$∀n$ ∈ N : Σ 
n(n + 1)(2n + 1)

$1^2$ + $2^2$ + $3^2$ + . . . + $n^2$ =1/6n(n + 1)(2n + 1)

when n =3, 1+4+9 = 1/2(28)=14

assume $∀n$ [ A$(n)$ ⇒ A$(n+1)$] 

left side 1/6n(n + 1)(2n + 1) + $(n+1)^2$ = (n+1)[1/6n(2n+1)+(n+1)]

right side 1/6(n+1)(n + 2)[2(n+1) + 1]= 1/6(n+1)[2n(n+1)+]

finally, we can prove left side = right side

so, it is true.

## 3a.

$4^n$ − 1 is divisible by 3

set x, n integer,  $4^n$ − 1 = 3x

when n=1, 3x=3

assume $∀n$ [ A$(n)$ ⇒ A$(n+1)$] 

$4^(n+1)$ − 1 =  $4^n$4 − 1 

4(3x+1)-1 = 12x+3 = 3(4x+1) 

so it is true

## 3b.

(n + 1)! > $2^(n+3)$  for all n ≥ 5.

when n =6,  prove (6 + 1)! > $2^(6+3)$  true

assume $∀n$ [ A$(n)$ ⇒ A$(n+1)$] 

Prove (n + 1)! (n+1) > $2^(n+4)$

(n + 1)! (n+1)> $2^(n+3)$ (n+1) = 2($n^2$+4n+3)= 2[n(n+4)+3]

Because n ≥ 5.

obviously 2n(n+4)+6 > $2^(n+4)$

so (n + 1)! (n+1)> $2^(n+4)$

and (n + 1)! > $2^(n+3)$ is proved

assume $∀n$ [ A$(n)$ ⇒ A$(n-1)$] 

 C= (n)! > $2^(n+2)$ 

A/C =  (n+1)  > 2

It is true.

## 3c.

Σ r.r! = (n + 1)! − 1

set r = 1 , it is true

r=n, the equation should be

1/2n(n + 1)n! = (n + 1)! − 1

assume $∀n$ [ A$(n)$ ⇒ A$(n+1)$] 

r = n+1 

1/2(n+1)(n + 2)(n+1)! = (n + 2)! − 1

1/2(n+1)(n + 2)! = (n + 2)! − 1