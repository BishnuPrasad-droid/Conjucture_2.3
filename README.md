# Conjucture_2.3

# Proof of Conjecture 2.3

## Author
**Bishnu Prasad Swain**

## Date
June 2026

---

## Overview

This document provides a complete proof of **Conjecture 2.3**, showing that the original geometric condition admits exactly one positive solution.

The proof transforms the geometric equation into an algebraic quartic polynomial and demonstrates that the quartic factors as

\[
P(x)=(x^2-1)Q(x),
\]

where \(Q(x)\) is strictly positive for all \(x>0\). Consequently, the only positive root of the quartic is \(x=1\).

---

## Mathematical Setting

Let

\[
\alpha=\theta_2-\theta_4,\qquad
\beta=\theta_3-\theta_4,
\]

with

\[
0<\beta<\alpha<2\pi.
\]

Define

\[
p_{24}=\cos\alpha,\qquad
p_{34}=\cos\beta,\qquad
p_{23}=\cos(\alpha-\beta).
\]

Using trigonometric identities from Lemma 2.2, the constant

\[
c=
\frac{1-p_{24}-p_{34}+p_{23}}
     {2\sqrt{(1-p_{24})(1-p_{34})}}
\]

simplifies to

\[
c=\cos\frac{\alpha-\beta}{2}.
\]

---

## Original Equation

The geometric condition is

\[
\frac{x\bigl(x^{2}-x(p_{24}+p_{34})+p_{23}\bigr)}
{\sqrt{(x^{2}+1-2xp_{24})(x^{2}+1-2xp_{34})}}
=c.
\]

Squaring both sides and clearing denominators produces the quartic equation

\[
P(x)=0.
\]

---

## Main Results

### 1. Verification of Roots

The quartic polynomial satisfies

\[
P(1)=0,
\]

and

\[
P(-1)=0.
\]

Hence

\[
(x^2-1)
\]

is a factor of \(P(x)\).

---

### 2. Factorization

The quartic factors as

\[
P(x)=(x^2-1)Q(x),
\]

where

\[
Q(x)
=
4\sin^2\frac{\alpha}{2}\sin^2\frac{\beta}{2}(x-1)^2
+
4\left(
\sin\frac{\alpha}{2}\cos\frac{\beta}{2}
-
\sin\frac{\beta}{2}\cos\frac{\alpha}{2}
\right)^2x.
\]

Using

\[
\sin\frac{\alpha}{2}\cos\frac{\beta}{2}
-
\sin\frac{\beta}{2}\cos\frac{\alpha}{2}
=
\sin\frac{\alpha-\beta}{2},
\]

the second term becomes

\[
4(1-c^2)x.
\]

---

### 3. Positivity of \(Q(x)\)

For \(x>0\),

- the first term is non-negative,
- the second term is strictly positive.

Therefore

\[
Q(x)>0
\qquad (x>0).
\]

---

### 4. Uniqueness of the Positive Root

Since

\[
P(x)=(x^2-1)Q(x),
\]

and \(Q(x)>0\) for all positive \(x\),

\[
P(x)=0
\iff
x^2-1=0.
\]

Thus the only positive root is

\[
x=1.
\]

---

## Conclusion

The quartic equation obtained from the geometric condition has exactly one positive solution:

\[
x=1.
\]

Therefore **Conjecture 2.3 is proved**, and the associated geometric condition admits a unique positive solution.

---

## Repository Contents
