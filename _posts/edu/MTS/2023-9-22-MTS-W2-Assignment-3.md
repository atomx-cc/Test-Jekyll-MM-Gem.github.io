---
title: "Mathematical Thinking Stanford, W2 Assignment 3"
date: 2023-9-22
categories:
  - IT
tags:
  - Internet
  - Math & CS
  - AI
---

# 1. D, Y, T

a. T ⇒ [D ∧ Y]

b. D ⇒ ¬ Y

c. ¬ D ⇒  ¬ T 

d. T ⇒  ¬ (D ∧ Y)

e. ¬ D ∧ Y ∧ T ,  T ⇒ [¬ D ∧ Y], following means “then or and”, they are all conjunctions relationship. 

f. (T ∧ Y) ⇒ ¬ D , T ⇒ [Y ⇒ ¬ D]  

g. T ⇒ [D ⇔ Y], T⇒ [(D ⇒Y) ∧ (Y⇒D)]

h. T ⇒ (¬D ∧ Y) ∨ (D ∧ ¬Y)

# 2. Truth table

| **φ** | **¬φ** | **ψ**
 | **φ⇒ψ** | **¬φ∨ψ** |
| --- | --- | --- | --- | --- |
| T | F | T | T | T |
| T | F | F | F | F |
| F | T | T | T | T |
| F | T | F | T | T |

# 3 Conclusions of above table

φ⇒ψ = ¬φ∨ψ

# 4 truth table

| **φ** | **ψ** | **¬φ** | **φ⇒ψ** | φ̸⇏ψ | φ∧¬ψ
 |
| --- | --- | --- | --- | --- | --- |
| T | T | F | T | F | F |
| T | F | F | F | T | T |
| F | T | T | T | F | F |
| F | F | T | T | F | F |

# 5 Conclusions of above table

φ̸⇏ψ = φ∧¬ψ

# Woman swerves and sleeping dogs

V = Views Dog

S =  Swerves

| V | S | V**⇒S** |
| --- | --- | --- |
| T | T | T |
| T | F | F |
| F | T | T |
| F | F | T |