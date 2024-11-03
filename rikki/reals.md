# Number Sets
We build up the basic sets of numbers that we work with in elementary mathematics by starting with the numbers that we use to count and adding things so that the sets can be closed under different kinds of operations.

## Natural numbers
The _Natural Numbers_ are the numbers $0, 1, 2, ... , n, n+1 ...$ that we use to count.  We use the symbol $\mathbb{N}$ to denote the natural numbers.

The natural numbers are closed under addition and multiplication - i.e. if $m$, and $n$ are natural numbers, then $n + m$ and $n \cdot n$ are both natural numbers.  We often omit the $\cdot$ and just write $mn$ for $m \cdot n$.

We call the number $0$ the _addititive identity_ because it satistfies $n + 0 = n$ for every natural number $n$.

Similarly, $1$ is called the _multiplicative identity_ because $n \cdot 1 = n$ for all $n \in \mathbb{N}$

Note that $\mathbb{N}$ is not closed under either subtraction or division.  Sometimes we can "invert" addition and multiplication and sometimes we can't.  For example $8$ can be divided by $2$ but not by $6$ and $5 - 3$ is a natural number but $5 - 7$ is not.

We look at subtraction and division as the _inverses_ of addition and multiplication, respectively.  In order for number sets to be closed under these operations, we need to have _additive inverses_ and _multiplicative inverses_.

The _additive inverse_ of a number $n$, is the number $-n$ such that $n + -n = 0$.  So $-n$ "inverts" or reverses the operation of adding $n$, i.e., if $m$ is another number, $m + n + -n = m$ - adding $n$ then adding $-n$ is a no-op.

Similarly, the _multiplicative inverse_ of $n$ is the number $n^{-1}$ such that $n \cdot n^{-1}$ = 1.  Here again, the intuition is that multiplying by $n^{-1}$ cancels the effect of multiplying by $n$.

The only number in $\mathbb{N}$ that has an additive inverse is $0$ and the only number with a multiplicative inverse is $1$. 

## Integers
The _Integers_ are what we get when we add additive inverses for all of the natural numbers.  We use $\mathbb{Z}$ to represent the integers.  So  $\mathbb{Z} = ... -2, -1, 0, 1, 2, ... $

The integers are closed under multiplication and subtraction, but not division.  To be able to divide, we need to add fractions.

All of the number sets we are going to work with (including $\mathbb{N}$) satisfy the following laws governing how addition and multiplication work:

(Associative Law) $a(bc) = (ab)c$

(Distributive Law) $a(b+c) = ab + ac$

(Commutative Law) $a + b = b + a$

The fact that $\mathbb{Z}$ is closed under addition and multiplication, has additive inverses, has additive and multiplicative identity elements and satisfies the laws above means that $\mathbb{Z}$ is a _ring_.

## Rationals
The _Rational Numbers_ are what we get when we add multiplicative inverses to the integers.  We use $\mathbb{Q}$ to represent the rational numbers.  Formally, we can define the rationals in terms of the integers:

$\mathbb{Q} = \\{m/n : m, n \in \mathbb{Z}, n \ne 0 \\}$

So $\mathbb{Q}$ is the set of all fractions that can be formed from integers.



