# Number Sets
We build up the basic sets of numbers that we work with in elementary mathematics by starting with the numbers that we use to count and adding things so that the sets can be closed under different kinds of operations.

## Natural numbers
The _Natural Numbers_ are the numbers $0, 1, 2, ... , n, n+1 ...$ that we use to count.  We use the symbol $\mathbb{N}$ to denote the natural numbers.

The natural numbers are closed under addition and multiplication - i.e. if $m$, and $n$ are natural numbers, then $n + m$ and $n \cdot n$ are both natural numbers.  We often omit the $\cdot$ and just write $mn$ for $m \cdot n$.

We call the number $0$ the _addititive identity_ because it satistfies $n + 0 = n$ for every natural number $n$.

Similarly, $1$ is called the _multiplicative identity_ because $n \cdot 1 = n$ for all $n \in \mathbb{N}$

Note that $\mathbb{N}$ is not closed under either subtraction or division.  Sometimes we can "invert" addition and multiplication and sometimes we can't.  For example $8$ can be divided by $2$ but not by $6$ and $5 - 3$ is a natural number but $5 - 7$ is not.

We look at subtraction and division as the _inverses_ of addition and multiplication, respectively.  In order for number sets to be closed under these operations, we need to have _additive inverses_ and _multiplicative inverses_.

The _additive inverse_ of a number $n$, is the number $-n$ such that $n + -n = 0$.  So $-n$ "inverts" or reverses the operation of adding $n$, i.e., if $m$ is another number, $m + n + -n = m.$ Adding $n$ then adding $-n$ is a no-op.

Similarly, the _multiplicative inverse_ of $n$ is the number $n^{-1}$ such that $n \cdot n^{-1}$ = 1.  Here again, the intuition is that multiplying by $n^{-1}$ cancels the effect of multiplying by $n$.

The only number in $\mathbb{N}$ that has an additive inverse is $0$ and the only number with a multiplicative inverse is $1$. 

### Prime numbers

We say that a natural number $n$ *divides* another natural number $m$ when $m$ can be written as a product of $n$ and another natural number.  So for example, $3$ divides $12$ since $12 = 3 \cdot\ 4$. When $m$ divides $n$ we say that $m$ is a *factor* of $m$. Numbers that have no factors other than $1$ and themselves are called *prime numbers*.  The first few prime numbers are $2, 3, 5, 7, 11, 13.$ Here are some important facts about prime numbers that we won't prove in this swim.  See the [number theory]() swim for a deep dive into the wonders of prime numbers.

 1. There are infinitely many prime numbers.  There is no largest prime number.
 2. The distance between consecutive primes gets larger and larger as you go out farther in the sequence.
 3. (Fundamental Theorem of Arithmentic)  Any natural number $n$ can be written in exactly one way as a product of prime numbers.

The factorization in 3. is called the *prime factorization* of the number.  Here are some examples

   $4 = 2^2 $

   $24 = 2^3 3$

   $72 = 2^3 3^2$

   $225 = 3^2 5^2$

  Write the prime factorization of each of the following numbers:

  $186, 36, 108, 1000, 550, 1000000$

  Find the smallest number that is a multiple of both $2^2 \cdot 5^2 \cdot 7^3 \cdot 11^3$ and $2^3 \cdot 7^2 \cdot 11^2 \cdot 13$.

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

If $b > 1$, $c$ will be a smaller number than $cb$.  When the numberator and denominator of a fraction have no common factors, the fraction is said to be _in lowest terms_.

### Fun with rationals
Write a fraction in lowest terms that is equal to each of the following

 1. $\frac{2}{9} + \frac{1}{6}$
 2. $\frac{11}{8} - \frac{2}{3}$
 3. $\frac{3}{8} \cdot \frac{1}{6}$
 4. $\frac{3}{7} \cdot \frac{1}{\frac{1}{6}}$
 5. $\frac{3}{7} \cdot 21$
 7. $(\frac{1}{5} + \frac{1}{3})(\frac{1}{5} - \frac{1}{3})$  do this both directly by adding the insides first and using the distributive law
 8. $\frac{\frac{2}{5}}{4}$

Can you think of a better way to find the least common multiple of two integers without looking at a lot of numbers?

## Real numbers

The rational numbers seem like they should be all the numbers that we need. They are closed under addition, subtraction, multiplication and division (as long as the denominator is not $0$). Given that we can make the denominators as large as we like, it would seem that we could represent any value using rational numbers. This is not true. Euclid showed that $\sqrt{2}$ can't be rational.  There are in fact many, many magnitudes that can't be expressed exactly as quotients of integers. Adding all of these numbers to the rationals makes the _real numbers_, which we call $\mathbb{R}$.  

While the real numbers are indeed a much bigger set than the rationals, the rationals are _dense_ in the reals. You can't go anywhere on the real line without bumping into a rational.  They own a house in every neighborhood.

More precisely, for any real number $r$ and any positive number $\epsilon$, the interval of width $\epsilon$ around $r$ contains a rational (actually infinitely many rationals). It's not hard to see this when you observe that decimal representations with any number of digits to the right of the decimal place are all rational numbers.  The number 3.14159 is the same as 314159/10000.  So if you consider any real number $r$, you can start with the closest integer to it, then look at tenths, hundredths, etc and you can get arbitrarily close to it with a rational number.

Here is a modified version of Euclid's proof that $\sqrt{2}$ can't be rational.  It is a proof by contradiction. In this manner of proof, one starts by assumming the negation of the statement to be proved and then derives a contradiction, thus proving that the statement to be proved must be true.

Suppose, then, that $\sqrt{2}$ is rational. Then we must be able to write $\sqrt{2} = m/n$  where $m$ and $n$ are integers.  Any fraction can be written in lowest terms, so assume without loss of generality that $m$ and $n$ have no common factors (otherwise those could be cancelled to reduce the fraction to lowest terms).  Given that  $\sqrt{2} = m/n$ it follows that  $\sqrt{2} \cdot \sqrt{2} = (m/n) \cdot (m/n$). Multiplying this out gives

$2 = m^2/n^2$

Multiplying both sides above by $n^2$, we get $2n^2 = m^2$.  So $m \cdot m$ is even.  That means $m$ must be even, since the square of an odd numbers is always odd. (Odd numbers always take the form $2k + 1$ for some $k$. That means the square of an odd number is something of the form $(2k + 1)(2k +1) = 4k^2 + 4k + 1 = 2(k^2 + 2) + 1$,  which is of the form $2k + 1$ with $k^2 + 2$ playing the role of $k$.)

Now consider the prime factorizations of $m$ and $n$.  Since $m$ is even, its prime factorization must include a $2$.  If $n$ is also even, then $m$ and $n$ share a common factor, contradicting our assumption that the fraction is in lowest terms.  So $n$ must be odd which means its prime factorization can't include any power of $2$.  But since $m$ is even, the power of $2$ in the prime factorization of $m^2$ has to be at least $2$.  But if $n$ does not contain any $2's$ in its expansion, the quotient $m^2/n^2$ has to have $2^2$ in its expansion.  But the quotient is only $2$, which is a contradiction.

## Real vectors

A _real vector_ is an finite ordered list of real numbers.  The number of elements in the list is the _dimension_ of the vector. The individual elements in the list are called the _components_ of the vector.  We represent vectors by listing their components inside parentheses.  For example,

$(0,1)$ is a 2-dimensional real vector with first component $0$ and second component $1$.

$(-7, \sqrt{3}, \pi)$ is a 3-dimensional real vector

$(0,0,0,0,0)$ is a 5-dimensional real vector.

For each $n \geq 1$, we use $\mathbb{R}^n$, pronounced "R n" to denote the set of all real vectors of dimension $n$.

For dimensions $2$ and $3$ we can visualize real vectors.  We visualize 2-dimensional vectors using the _Cartesian Coordinate Plane_

![image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSVcsw3ZkrgU8LSlxRD6ubSFNI3Poy-UdaBIQ&s)


The picture shows the real vector $(6, 4)$ in $\mathbb{R}^2$ represented by the point with $x$ coordinate $6$ and $y$ coordinate $4$.

We can visualize points (vectors) in $\mathbb{R}^3$ by adding a third coordinate axis.

![image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSXjKt_0_ryskvg0taTZ0aITw-w0rrBIog44w&s)

We can compute the distance between points in $\mathbb{R}^2$ using the pythagorean theorem:

![image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR4AkZYNs0Z7Y85-m7ifSmwuGhI6nAsVPeRK35r57kvLw7yVVq4VZO3U4kBrjNfnnB8QCA&usqp=CAU
)

The distance $d$ above is $\sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}$.

The same can be done for points in $\mathbb{R}^3$

![image](https://i.ytimg.com/vi/Y9-7SjOxwZw/maxresdefault.jpg
)

For real numbers, $\lvert a - b \rvert$ can be viewed as the distance between $a$ and $b$ (draw some points on the number line and this should be clear).  We use this same notation for the distance between points in higher dimensional spaces.  So for example, $\lvert (2,3) - (1,1) \rvert$ represents the distance between $(2,3)$ and $(1,1)$.

There are other ways to define distance between points in $\mathbb{R}^n$, but the above definition, which extends naturally to any $n$-dimensional real vector space, is the most common.  The distance measure that it represents is called _Euclidean distance_.

All distance measures satisfy what is known as the _triangle inequality_, which states that the distance between point $a$ and point $c$ is less than or equal to the distance between point $a$ and point $b$ plus the distance between point $b$ and point $c$.  In the notation above, that means for any real vectors $a, b, c$

$\lvert a - b \rvert + \lvert b - c \rvert \le \lvert a - c \rvert$.

Intuitively, this says that going directly from $a$ to $c$ can't be a longer trip than doing the same but making a side trip through $b$.

Prove that with distance defined as above, the triangle inequality holds in $\mathbb{R}^2$.

What has to be true about $a$, $b$ and $c$ in $\mathbb{R}^2$ in order for $\lvert a - b \rvert + \lvert b - c \rvert = \lvert a - c \rvert.$  Prove your assertion.






