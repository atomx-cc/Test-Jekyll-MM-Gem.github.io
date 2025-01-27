---
title: "Mathematical Thinking Stanford, W8 Quiz"
date: 2023-9- 00 
categories:
  - IT
tags:
  - Internet
  - Math & CS
  - AI
---


**least upper bound**

A set A of reals can have at most one least upper bound.

if a is LUB, then a≤b

if b is LUB, then b≤a

if a, b are both two LUBs, then b=a, 

such as {42} has the only element 42 as both an upper bound and a lower bound.

**lower bound**

if a set A of reals has a lower bound, it has infinitely many lower bounds. 

if a is a lower bound of A, then so is any b<a.

**Set of reals is infinite** 

if a set A of reals has both a lower bound and an upper bound, then it is infinite.

i.e. let A=[0,1], it is an infinite set of real numbers.

**Least upper bound of integers set**

-1 is the least upper bound of the set of negative integers, considered as a subset of the reals. 

the set of negative integers {…… n, -3, -2, -1}

**Sandwich Theorem(Squeeze Theorem)**

the Sandwich Theorem say that

if $\left\{{a_n}\right\}_{\left(n=1\right)}^∞$, $\left\{{b_n}\right\}_{\left(n=1\right)}^∞$, $\left\{{c_n}\right\}_{\left(n=1\right)}^∞$ are sequences such that, 

from some point $n_0$ onwards, $a_n$ ≤ $b_n$ ≤ $c_n$, 

and if  $\lim _{n→∞}a_n$ =  $L$ , $\lim _{n→∞}c_n$ =  $L$ 

then $\left\{{b_n}\right\}_{\left(n=1\right)}^∞$ is convergent, and $\lim _{n→∞}b_n$ =  $L$ 

how to prove by the Sandwich Theorem ?

Theorem  $\lim _{n→∞}$$\frac{\left(\sin n\right)^{2\ }}{3^n}$ = 0

proof: for any n,  0≤$\frac{\left(\sin n\right)^{2\ }}{3^n}$ ≤ $\frac{1\ }{3^n}$

clearly, $\lim _{n→∞}$$\frac{1\ }{3^n}$ = 0 

0≤$\frac{\left(\sin n\right)^{2\ }}{3^n}$ ≤ 0

hence by the Sandwich Theorem, 

$\lim _{n→∞}$$\frac{\left(\sin n\right)^{2\ }}{3^n}$ = 0

as required.

# Peer graded Assignment

1. $(∃m∈ N)(∃n∈ N)(3m+5n=12)$

Answer: this statement is false.

Prove: set *n*=2, the closer possible solution is m=1, then 3m+5n=13;

if n>2, then 3m+5n>13; 

set m=2, the closer possible solution is n =, then 3m+5n=11;

if m>2, then 3m+5n>11, but never could be 12 by natural number; 

There doe not exist nature number n, m that satisfy the equation.

$(¬∃m ∈ N) (¬∃n ∈ N)$(3m+5n=12)

So, it is proved.

1. **The sum of any five consecutive integers is divisible by 5 (without remainder).**

Answer: the statement is True.

Prove: set (*n* ∈ *Z*), n could be anyone of the integer set,

the sequence of any five consecutive integers are:
$*n, n+1, n+2, n+3, n+4*$

The sum of above numbers sequence:
$Σ(n,n+1,n+2,n+3,n+4)=  5n+10 = 5(n+2)$

obviously, 5(n+2) is divisible by 5.

The statement is proved.

1. **For any integer *n*, the number $*n^2+ n +1$*  is odd.**

Answer: the statement is True.

Prove: by induction

set n =1, then **$*n^2+ n +1$***  = 3, it is odd.

Assume for any integer n, it is true.

$∀n[A(n)⇒A(n+1)]$

set n = n+1, then  $(n+1)^2+(n+1)+1=n^2+3n+3=(n^2+n+1)+2(n+1)$

clearly that  2(*n*+1) is even or zero, and **$*n^2+ n +1$***   is odd,

when number odd add even(or zero), it could only produce odd possibly,

so it is proved.

1.  **every odd natural number is of one of the forms 4*n*+1 or 4*n*+3, where *n* is an integer.**

Answer: the statement is true.

Prove: by induction 
set (*n* ∈ *Z*), n could be anyone of the integers.
when n=0, 4n+1=1, 4n+3=3; 
when n=1, 4n+1=5, 4n+3=7;

{1, 3, 5, 7} are odd natural numbers.

Assume for any integer n, it is true.

$∀n[A(n)⇒A(n+1)]$

set n = n+1, then the forms are  4(*n*+1)+1,4(*n*+1)+3

4(*n*+1)+1=(4*n*+1)+4,4(*n*+1)+3=(4*n*+3)+4

clearly that  any number odd add an even number 4, it could only produce odd possibly,

so, it is proved.

1. **for any integer *n*, at least one of the integers *n, n*+2, *n*+4 is divisible by 3.**

Answer: 

~~the statement is true.(the prompt does not require to answer true or false)~~

Prove: by the division theorem. ~~by induction(the main method is not induction).~~

set n=1, n+2= 1x3 ; n=2, n+4 = 2x3, so on, etc.

assume for any integer *n*, the statement is true.

set n=3k, then **n** is divisible by 3;

set n=3k+1, then ***n*+2=3(k+1)** is divisible by 3;

set n=3k+2, then ***n*+4=3(k+2)** is divisible by 3;

for n = n+1, 

**the integers *n+1, n*+3, *n*+5** 

set n=3k, then ***n*+3=** **3(k+1)** is divisible by 3;

set n=3k+1, then ***n*+5=3(k+2)** is divisible by 3;

set n=3k+2, then ***n*+1=3(k+1)** is divisible by 3;

by reasoning they are all divisible by 3

It is proved.

1. **prove the only prime triple (i.e. three primes, each 2 from the next) is 3, 5, 7.**

by contradiction

Assume there are more prime triples.

set the prime triples are P, P+2, P+4

and set P is the set of Prime.

when P=3, the prime triple is **3, 5, 7.**

according to question 5: **for any integer *n*, at least one of the integers *n, n*+2, *n*+4 is divisible by 3.**

except  P=3, the other all results will get sets that could be divisible by 3, 

so they are not prime.

it proves the only prime triple is **3, 5, 7.**

1. **Prove that for any natural number $2^2+2^2+2^3+…+2^n=2^(n+1)−2$**

Prove: by induction.

set n = 1 , left side is 2, left side is 2, they are equal to each other.

Assume for any integer n, it is true.

$∀n[A(n)⇒A(n+1)]$

set n = n+1,  for left side of euqation: 

**$2^2+2^2+2^3+…+2^n+2^(n+1)$ =**

$2^(n+1)−2 +2^(n+1)$ = $2[2^(n+1)−1]$

for the right side of equation:
$2^((n+1)+1)−2=2[2^(n+1)]−2=2[2^(n+1)−1]$

both sides are equal to each other.

So it is proved

1. **the sequence $\left\{Ma_n\right\}_{n=1}^{\ ∞}$ tends to the limit $ML.$** 

Prove:  

give 𝜀>0,

$lim _{n→∞}a_n =  L$ , $M>0$

set |A| = | $\left\{a_n\right\}_{n=1}^{\ ∞}$ $−L$ | < 𝜀

such that |A| <  𝜀/𝑀

 $M |A|$ <  𝜀,  $|MA|$ <  𝜀, 

 | $\left\{Ma_n\right\}_{n=1}^{\ ∞}$ $−ML$ | < 𝜀

by the definition of limts.(very important for the conclusion statement)

hence, it proves the sequence $\left\{Ma_n\right\}_{n=1}^{\ ∞}$ tends to the limit $ML.$ 

1. **Prove that your example has the stated property.**

${∩}_(n=1) ^∞$$∩_(n=1) ^∞$ *An*= { ${x∣(∀n)(x∈An)}$ }

Prove :

∩𝑛=1∞𝐴𝑛=∩^∞_{𝑛=1}𝐴_𝑛 = 
 
 ∩n=1∞An= { x∣(∀n)(x∈An)x|(∀n) (x ∈ An)x∣(∀n)(x∈An) }

set  x=1/nx= 1/n  x=1/n

∩𝑛=1∞𝐴𝑛=∩^∞_{𝑛=1}𝐴_𝑛 = 
 
 ∩n=1∞An= { x∣(∀n)(x∈An)x  |(∀n) (x ∈ An)x∣(∀n)(x∈An) }

so AnAnAn = (  0,10, 10,1],

set  x=1/(n+1)x= 1/(n+1)  x=1/(n+1),
∩𝑛=1∞𝐴(𝑛+1)=∩^∞_{𝑛=1}𝐴_(𝑛+1) = 
 
 ∩n=1∞A(n+1)= { x∣(∀(n+1)[x∈A(n+1)]x  |(∀(n+1) [x ∈ A(n+1)]x∣(∀(n+1)[x∈A(n+1)] } ,

A(n+1)A(n+1)A(n+1) =  (  0,1/20, 1/20,1/2],

1/(n+1)<1/n1/(n+1) < 1/n 1/(n+1)<1/n,  1/2<1 1/2 < 11/2<1,

so  A(n+1)⊂AnA_(n+1) ⊂ A_nA(n+1)⊂An

When take n as a big number,

∩𝑛=1∞𝐴𝑛∩^∞_{𝑛=1}𝐴_𝑛
 
 ∩n=1∞An =  ∩𝑛=1∞A(n+1)∩^∞_{𝑛=1}A(n+1)
 
 ∩n=1∞A(n+1) =  ( 0, 0)  =∅= ∅=∅
so  A(n+1)=AnA_(n+1) =  A_nA(n+1)=An

it proves that for all nnn and ∩𝑛=1∞𝐴𝑛=∅∩^∞_{𝑛=1}𝐴_𝑛=∅
 
 ∩n=1∞An=∅

such that  A(n+1)⊂AnA_(n+1) ⊂ A_nA(n+1)⊂An


1. **Prove that your example has the stated property.**

Prove:

n∈Zn ∈ Zn∈Z, A(n+1)⊂AnA_(n+1) ⊂ A_nA(n+1)⊂An

set  x=0nx=\frac{0}{n}x=n0 ,

for ∩𝑛=1∞𝐴𝑛=∩^∞_{𝑛=1}𝐴_𝑛 =
 
 
 ∩n=1∞An=   {(x∣(∀n)(x∈An) (x |(∀n) (x ∈ An)(x∣(∀n)(x∈An) }

for any n, and n+1, x=0,

such that  ∩𝑛=1∞𝐴𝑛∩^∞_{𝑛=1}𝐴_𝑛
 
 ∩n=1∞An ={0}

it is the single real number in the set

so it is proved.


**Peer review:**

LaTeX entry is not supported, so almost all of the math notations are wrong or disordered in your solution. please post pdf or picture according to the instruction.

don’t make typos(拼写错误)