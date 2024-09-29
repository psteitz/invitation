## Function Definition

Suppose that $X$ and $Y$ are two sets.  A function from $X$ to $Y$ is a set of ordered pairs $(x,y)$ such that for every $x$ in $X$ there is exactly one $y$ in $Y$ such that $(x,y)$ is in the set.  Looked at another way, a function maps elements of its domain ($X$) into its range ($Y$). $X$ values are like keys in a dictionary for $Y$ values.

It is not required that every element of $Y$ is the image of some element of $X$ and there may be multiple $x$ values that map to the same $y$.  The only thing that is required is that for each $x$ in $X$ there is exactly one $y$ in $Y$ such that $(x,y)$ is in the function.  Instead of saying $(x,y)$ is in $f$, we write $f(x) = y$. We write $f : X \to Y$ to mean $f$ is a function with domain $X$ and range a subset of $Y$.

## Function examples and non-examples

We use $\mathbb{R}$ to represent the set of real numbers. For now, consider the real numbers to be all magnitudes
that can be measured off positively or negatively starting at 0.  All points on the number line.

Which of the following are functions?
 1. $\\{(a, 2a) : a \in \mathbb{R}\\}$
 2. $\\{(\sqrt(y), y) : y \in \mathbb{R}\\}$
 3. $\\{(x, y) : x \in \mathbb{R}$ and $y = 1$ if $y$ is rational, $0$ otherwise $\\}$
 4. $\\{(x,y) : (x,y)$ is a point on a circle of radius $1$ around $(0,0)\\}$

Provide an example of a function that maps multiple input values to the same output value.

The *graph* of a function $f:\mathbb{R} \to \mathbb{R}$ is the set of points $(x,f(x))$ for $x \in \mathbb{R}$.
Provide an example of a function $f$ whose graph can be drawn continuously without picking up your pencil.

A *polynomial function* is a function that computes a weighted sum of powers of its input.  For example, 
$f(x) = x^2 + 2x + 1$ and $g(x) = -8x^5 + 4x^3 + 2x^2 - 12x$ are polynomial functions. 

What does it tell you about the value $x$ and the polynomial function $p$ when $(x,0)$ is on the graph of $p$?

For $p(x) = x^2 + 2x + 1$, plot some points on its graph. Find the $x$ value that minimizes this function. 
It is clear from the graph that this function never takes a negative value.  Why is that?


## Function properties
A function is *injective* if different $x$ values map to different $y$ values.

A function is *surjective* if every element of the range appears among the values of the function.

A function that is both injective and surjective is called a *bijection*.  Bijective functions can be inverted. 

Provide examples of 
 * a function that is injective, but not surjective
 * a function that is surjective, but not injective
 * a bijection

A set is *countable* if there is an injective function from the set into the natural numbers.

Prove that if a set $A$ is countable then it can be listed out as $a_0, a_1, ... , a_{n-1}, a_n ...$

Prove that if $A$ and $B$ are infinite countable sets then there is a bijection between $A$ and $B$





