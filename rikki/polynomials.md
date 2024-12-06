# Polynomial Functions

## Polynomial definition
Polynomials are expressions of the form $a_nx^n + a_{n-1}x^{n-1} + ... + a_0$ where the $a$'s come from a set of coefficients
and the $x$ values are assumed to be in another set.  Polynomials over the real numbers with real coefficents are an important
class of real-valued functions of a real variable.

A _real polynomial_ $p$ of a real variable $x$ is a function of the form $p(x) = a_nx^n + a_{n-1}x^{n-1} + ... + a_0$
where $\\{a_0, ... , a_n\\} \subset \mathbb{R}$.  The number $n$ is the _degree_ of the polynomial.

We give special names to lower-degree polynomials.

| Degree    | Name | Example | Notes |
| -------- | ------- | ------- | ----- |
| 0   | constant | $p(x) = 0$ | Here $a_0 = 0$. Among polynomials, this polynomial is the additive identity (see below).|
| 1 | linear | $p(x) = 2x - 3$ | Here $a_1 = 2$ and $a_0 = -3$ |
| 2 | quadratic | $p(x) = 4x^2 + x - 7$ | $a_2 = 4, a_1 = 1, a_0 = -7$|
| 3 | cubic | $p(x) = \pi x^3 - 1$| This one has some "missing terms" which means their coefficents are $0$:  $a_3 = \pi, a_2 = 0, a_1 = 0, a_0 = -1$. All of the other examples are _rational_ polynomials, since all of their coefficients are from $\mathbb{Q}$, but this one has an irrational coefficient, $\pi$.|

## Adding and multiplying polynomials
### Adding polynomials
To add polymials, we just add coefficients of corresponding terms.  For example, if $p(x) = 2x^2 + 3x + 4$ and
$q(x) = x^4-x^2 -x$ then $p(x) + q(x) = x^4 + x^2 + 2x + 4$.

Formally, suppose that 

$p(x) = a_nx^n + a_{n-1}x^{n-1} + ... + a_0$ and

$q(x) = b_mx^m + b_{m-1}x^{m-1} + ... + b_0$

Let D be the maximum of $m$ and $n$ and let let d be the minimum. 

If the polynomials have the same degree, these are equal and the second term in the sum below drops out.

$p(x) + q(x) = \sum_{i = 0}^{d}{(a_i + b_i})x^i + \sum_{i = d}^{D}{c_i x^i}$ where the $c_i$ are equal to 
$a_i$ values if $p$ is the higher-degree polynomial or $b_i$ if $q$ has higher degree.

Add the following pairs of polynomials

$p(x) = x - 1$

$q(x) = \frac{1}{2} x^4 - 2x^3 + x + 7$

---

$p(x) = 3x^7 + 4x^5 + x^3 + x$

$q(x) = x^6 - x^4 + x^3 + x^2 - 6$

---
    
$p(x) = x$

$q(x) = 1$

---
    
$p(x) = 3x^7 + 4x^5 + x^3 + x$

$q(x) = 0$

---    

### Multiplying polynomials
Multiplying polynomials uses the distributive law.  When you multiply two sums together, the distributive law means that you have to add up all of the pairwise products that you can make from the two sets. 

So if for example if $S_1 = 1 + 2 + 4$ and $S_2 = 5 + 7 + 9$ then

$S_1 S_2 = 1 \cdot 5 + 1 \cdot 7 + 1 \cdot 9 + 2 \cdot 5 + 2 \cdot 7 + 2 \cdot 9 + 4 \cdot 5 + 4 \cdot 7 + 4 \cdot 9$

When multiplying polynomials we have to collect up all of the terms created by applying the distributive law.  For example
if $p(x) = x - 1$ and  $q(x) = x + 1$ then

$p(x)q(x) = (x - 1) (x + 1) = x^2 + x + -1x + -1 \cdot 1 = x^2 - 1$

---

$p(x) = x-1$

$q(x) = x^{2}+x+1$

$p(x)q(x) = $

---

Let $p(x)= (x - 1)(x + 1)(x-4)$

What can you say about the graph of $p$?

Write $p$ in standard form.

## Factoring polynomials

## Roots of polynomials

## Real polynomials are a ring, but not a field

