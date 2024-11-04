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

So $\mathbb{Q}$ is the set of all fractions that can be formed from integers. In $\mathbb{Q}$ every integer other than $0$ has a multiplicative inverse. 

### Multiplication and division
To multiply fractions, we multiply numerators and denominators:

$\frac{m}{n} \cdot \frac{k}{l} = \frac{mk}{nl}$

Every rational number other than 0 has a multiplicative inverse.  If $r = m/n$ for integers $m$ and $n$, then $r^{-1} = n/m$ because $\frac{n}{m} \cdot \frac{m}{n}  = \frac{nm}{mn} = 1.$ 

We call $m/n$ the _reciprocal_ of $n/m$.  

The multiplicative inverse of a rational number is its reciprocal.

_To divide by a fraction is to multiply by its reciprocal._

$\frac{\frac{2}{3}}{\frac{7}{8}} = \frac{2}{3} \cdot \frac{8}{7}$

### Addition and subtraction
To add fractions, we have to express them with the same denominators. Getting the denominators the same is called finding a common denominator.  You can always use the product of the two denominators, because that product will for sure be divisible by each of them.  But there may be a smaller common multiple of the two denominators.  The least such integer is called the _least common multiple_ of the denominators.

To get to common denominators, we multiple the terms of a sum by $1$ in such a way that the denominators end up the same.  Here are some examples.

$1/2 + 2/3$

I want to find a commons multiple of $2$ and $3$.  The smallest number satisfying that is $6$, so $6$ is the _least common multiple_ of $2$ and $3$.  That means it is the _least common denominator_ for the fractions $1/2$  and $2/3$.  To do the sum, we convert the summands to be in sixths:

$\frac{1}{2} + \frac{2}{3} = \frac{1}{2} \cdot \frac{3}{3} + \frac{2}{3} \cdot \frac{2}{2} = 3/6 + 4/6 = 7/6$

$7/6 + 1/4$
In this case, there is a common multiple of $6$ and $4$ that is less than their product.  $12$ is a multiple of both $6$ and $4$.

$\frac{7}{6} + \frac{1}{4} = \frac{7}{6} \cdot \frac{2}{2} + \frac{1}{4} \cdot \frac{3}{3} = 14/12 + 3/12 = 17/12$

### Lowest terms
Because we can multiply any fraction by $n/n$ for every $n$, every rational number can actually be written in infinitely many ways as the quotient of two integers.

$2/7 = 4/14 = 6/21 = 8/28 ...$

When the numerator and denominator of a fraction have no common factors, we say the fraction is in _lowest terms_.  Any fraction can be reduced to lowest terms by finding common factors of its numerator and denominator and "cancelling" them.  This is OK because if

$\frac{m}{n} = \frac {ab}{cb}$    ($b$ is the common factor of $n$ and $m$)

then we can look at $\frac {ab}{cb}$ as the product of two fractions: $\frac{a}{c}$ and $\frac{b}{b}$.  Since $\frac{b}{b} = 1$, that gives us

$\frac{m}{n} = \frac {ab}{cb} = \frac{a}{c} \cdot \frac{b}{b} = \frac{a}{c}$.  

If $b > 1$, $c$ will be a smaller number than $b$.  When the numberator and denominator of a fraction have no common factors, the fraction is said to be _in lowest terms_.

### Fun with rationals
Write a fraction in lowest terms that is equal to each of the following

 1. $\frac{2}{9} + \frac{1}{6}$
 2. $\frac{11}{8} - \frac{2}{3}$
 3. $\frac{3}{8} \cdot \frac{1}{6}$
 4. $\frac{3}{7} \cdot \frac{1}{\frac{1}{6}}$
 5. $\frac{3}{7} \cdot 21$

Can you think of a better way to find the least common multiple of two integers without looking at a lot of numbers?

## Real numbers

The rational numbers seem like they should be all the numbers that we need. They are closed under addition, subtraction, multiplication and division (as long as the denominator is not $0$). Given that we can make the denominators as large as we like, it would seem that we could represent any value using rational numbers. This is not true. Euclid showed that $\sqrt{2}$ can't be rational.  There are in fact many, many magnitudes that can't be expressed exactly as quotients of integers. Adding all of these numbers to the rationals makes the _real numbers_, which we call $\mathbb{R}$.  

While the real numbers are indeed a much bigger set than the rationals, the rationals are _dense_ in the reals. You can't go anywhere on the real line without bumping into a rational.  They own a house in every neighborhood.

More precisely, for any real number $r$ and any positive number $\epsilon$, the interval of width $\epsilon$ around $r$ contains a rational (actually infinitely many rationals).



