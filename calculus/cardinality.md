# Cardinality
A set is finite if it has a finite number of elements. The cardinality of a finite set is the number of elements in the set.  So for example, the cardinality of {"dog", "pig"} is 2. 

It turns out that infinite sets aren't all the same size.

We order infinite sets by size by looking at whether or not they can be mapped into each other 1-1.

If a set can be mapped 1-1 into another set, we consider the first set as no larger than the second one. 

## Cardinality comparison
For sets $A$ and $B$, we write $\lvert{A}\rvert \le \lvert{B}\rvert$ and say $A$ _has cardinality less than or equal to the cardinality of_ $B$ if there is an injective function $f: A \to B$.

Show that the cardinality of the natural numbers is no larger than the cardinality of the even numbers.

Show that the cardinality of the integers is no larger than the cardinality of the natural numbers

Show that the cardinality of the rational numbers is no larger than the cardinality of the natural numbers

## Equal cardinalities
Two sets $A$ and $B$ have the same cardinality if there is a bijection $f:A \to B$.  In that case, we write $\lvert{A}\rvert = \lvert{B}\rvert$
The [Shroeder-Bernstein Theorem](https://en.wikipedia.org/wiki/Schr%C3%B6der%E2%80%93Bernstein_theorem) states that if $A$ has cardinality less than or equal to the cardinality of $B$ and $B$ has cardinality
less than or equal to the cardinality of $A$, then $A$ and $B$ have the same cardinality. In other words, 

$\lvert{A}\rvert \le \lvert{B}\rvert$ and $\lvert{B}\rvert \le \lvert{A}\rvert$ implies $\lvert{A}\rvert = \lvert{B}\rvert$ 

## Countable and uncountable sets

A set $A$ is _countable_ if $\lvert{A}\rvert \le \lvert\mathbb{N}\rvert$

The exercises above show that the integers and rational numbers are both countable sets.  It turns out that _the real numbers are uncountable_.

If $A$ is a set, then the _power set_ of $A$ is the set of all subsets of $A$.  For example, if $A = \\{0, 1, 2 \\}$ then the power set of $A$ is
$\\{\emptyset, \\{0,1,2\\}, \\{0,1\\}, \\{1,2\\}, \\{0,2\\}, \\{0\\}, \\{1\\}, \\{2\\}\\}$

Show that for every finite set $A$, the cardinality of the power set of $A$ is $2^{|A|}$.

Every real number has a unique binary expansion. Use this fact to show that the set of real numbers has the same cardinality as the power set of the natural numbers.

We use $2^{|A|}$ to denote the cardinality of the power set of an infinite set $A$.  The last exercise shows that $|\mathbb{R}| = 2^{|\mathbb{N}|}$.

The [_Continuum Hypothesis_](https://en.wikipedia.org/wiki/Continuum_hypothesis) states that there is no infinite cardinality between
that of the natural numbers and that of the real numbers.



