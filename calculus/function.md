## Function Definition

Suppose that $X$ and $Y$ are two sets.  A function from $X$ to $Y$ is a set of ordered pairs $(x,y)$ such that for every $x$ in $X$ there is exactly one $y$ in $Y$ such that $(x,y)$ is in the set.  Looked at another way, a function maps elements of its domain ($X$) into its range ($Y$). $X$ values are like keys in a dictionary for $Y$ values.

It is not required that every element of $Y$ is the image of some element of $X$ and there may be multiple $x$ values that map to the same $y$.  The only thing that is required is that for each $x$ in $X$ there is exactly one $y$ in $Y$ such that $(x,y)$ is in the function.  Instead of saying $(x,y)$ is in $f$, we write $f(x) = y$. We write $f : X \to Y$ to mean $f$ is a function with domain $X$ and range a subset of $Y$.

## Function examples and non-examples

We use $\mathbb{R}$ to represent the set of real numbers. For now, consider the real numbers to be all magnitudes
that can be measured off positively or negatively starting at 0.  All points on the number line.

Which of the following are functions?
 1. $\\{(a, 2a) : a \in \mathbb{R}\\}$
 2. $\\{(\sqrt y, y) : y \in \mathbb{R}\\}$
 3. $\\{(x, y) : x \in \mathbb{R}$ and $y = 1$ if $x$ is rational, $0$ otherwise $\\}$
 4. $\\{(x,y) : (x,y)$ is a point on a circle of radius $1$ around $(0,0)\\}$

Provide an example of a function that maps multiple input values to the same output value.

## Graphs of functions

The *graph* of a function $f:\mathbb{R} \to \mathbb{R}$ is the set of points $(x,f(x))$ for $x \in \mathbb{R}$.
Provide an example of a function $f$ whose graph can be drawn continuously without picking up your pencil.

A *polynomial function* is a function that computes a weighted sum of powers of its input.  For example, 
$f(x) = x^2 + 2x + 1$ and $g(x) = -8x^5 + 4x^3 + 2x^2 - 12x$ are polynomial functions. 

What does it tell you about the value $x$ and the polynomial function $p$ when $(x,0)$ is on the graph of $p$?

For $p(x) = x^2 + 2x + 1$, plot some points on its graph. Find the $x$ value that minimizes this function. 
It is clear from the graph that this function never takes a negative value.  Why is that?


## Function properties
### Mapping properties
A function is *injective* if different $x$ values map to different $y$ values.  Injective functions are sometimes called "one-to-one."  Bijective functions can be *inverted*.  Since for each value $y$ in the range of an injective function there is a unique value $x$ in the domain of the function such that $f(x) = y$, we can define the inverse function to be the function that maps $y$ back to $x$.  We sometimes write $f^{-1}$ for the inverse of $f$.  For example, if $f(x) = 2x$, then $f^{-1}(x) = \frac{1}{2}x$.  Intuitively, the inverse of an injective function reverses what the function does.

Why can't we define inverses for functions that are not one-to-one?  Illustrate your answer with an example.

A function is *surjective* if every element of the range appears among the values of the function. Surjective functions are sometimes called "onto."

A function that is both injective and surjective is called a *bijection*.  Bijective functions are "one-to-one and onto." 

Provide examples of 
 * a function that is injective, but not surjective
 * a function that is surjective, but not injective
 * a bijection

A set is *countable* if there is an injective function from the set into the natural numbers.

Prove that if a set $A$ is countable then it can be listed out as $a_0, a_1, ... , a_{n-1}, a_n ...$

Prove that if $A$ and $B$ are infinite countable sets then there is a bijection between $A$ and $B$

### Properties of functions from $\mathbb{R}$ to $\mathbb{R}$

In this section, all functions are assumed to be real-valued functions of a real variable.

A *constant* function is a function that takes just one value.  The graph of a constant function is a horizontal line.  For example, $f(x) = 1$ is constant function whose graph is a horizontal line one unit above the $x$ axis.

An *(strictly) increasing* function is function whose graph always looks "upward to the right."  Formally, a function is stricly increasing if $x_1 < x_2$ means that $f(x_1) < f(x_2)$.  The "strict" part is what makes the inequality among the $f(x)$ values strict.  If the function can be flat for some intervals, so that  $f(x_1) \le f(x_2)$ everywhere, but $f(x_1) = f(x_2)$ for some $x_1 < x_2$, we say that the function is *non-decreasing.*  Similar definitions hold for strict decreasing and non-increasing.

The increasing / decreasing definitions can be applied to intervals.  For example, the function $f(x) = x^2$ is strictly decreasing over the interval $(-\infty, 0)$ and strictly increasing over $(0,\infty)$.

Draw the graphs of the following functions and find the intervals over which they are increasing or decreasing.

 1. $f(x) = 2x$
 2. $f(x) = \left|x\right|$
 3. $f(x) = (x+1)(x-1)x$






