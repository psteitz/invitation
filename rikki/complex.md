# Complex Numbers
## Definition
A complex number is a number with two parts: a _real_ part and an _imaginary_ part.

We often write complex numbers $z$ in the form $z = a + bi$ where $a$ and $b$ are
real numbers and $i$ is the "imaginary unit", $\sqrt{-1}$.

We use $\mathbb{C}$ to denote the complex numbers.  We consider the real numbers, $\mathbb{R}$ to be a subset
of the $\mathbb{C}$, consisting of the complex numbers that have $0$ as their imaginary part.

We visualize complex numbers as points in the _complex plane_.  

The complex plane has the real line as its x axis and the imaginary dimension on the y axis.
The complex number $x + yi$ corresponds to the point $(x,y)$.

![image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQg2hPuW3bnRkQZHxXRjO6GduQQIJSS-u2LWw&s)

The _modulus_ of a complex number $z = x + yi$ is the distance of $(x,y)$ from the origin in the complex plane.
We use $|z|$ to represent the modulus of $z$.

Write a formula for the modulus of $z$ in terms of $x$ and $y$.

When $z = x + iy$ is plotted in the complex plane, the angle of an arrow that points to it, starting at the origin,
is called the _argument_ of $z$ or $arg(z)$. Arguments are measured in radians.

Find the modulus and argument for each of the following complex numbers

 1. $1 + i$  
 2. $0 + i$  (normally we would omit the $0$ and just say $i$ here)
 3. $-2  + 0i$ (similarly, no need to write $0i$ here)
 4. $\sqrt{3} + i$

## Arithmetic operations
To add two complex numbers, we add their real and imaginary parts: 

$(a + bi) + (c + di) = (a + c) + (b + d) i$

Multiplication uses the distributive law:

$(a + bi)(c + di) = ac + adi + bci + bdi^2 = (ac - bd) + (ad + bc)i$ 

$bdi^2 = -bd$ because $i^2 = -1$

Show that when two complex numbers are multiplied, the argument of the product is the sum of the arguments - i.e.

$arg(z_1 z_2) = arg(z_1) + arg(z_2)$

For any complex number $z = x + yi$, $-z = -x - yi$ is the _additive inverse_ of $z$. Note that for all $z$, $z + -z = 0 + 0i$
We refer to $0 + 0i$ as complex zero.  Complex zero is also the _additive identity_ among complex numbers - i.e., $z + (0 + 0i) = z$ for all $z$.

Subtraction and divison are defined the same way we do with real numbers, by making them the inverses of addition and multiplication, respectively.

$z - w$ is the complex number that you have to add to $w$ to get $z$ so $w + (z - w ) = z$

Write the definition of complex subtraction that will make this work.

$(a + bi) - (c + di) = $???

To define complex division, we would like to express $\frac{a + bi}{c + di}$ in the form $x + yi$.  
To get to that form, we can use a trick to clear the denominator. The trick uses what we call _complex conjugation_.

For a complex number $z = x + yi$, we define the _conjugate_, $conj(z)$ to be $x - yi$. So conjugation is just flipping the sign on the imaginary part of the number.  Graphically, this amounts to reflecting the point across the $x$ axis in the complex plane. 

Show that for all $z$
1.  $arg(conj(z)) = -arg(z)$
2.  $|z| = |conj(z)|$
3.  $z \cdot conj(z)$ is a real number - i.e. $z \cdot conj(z)$ has $0$ as its imaginary part.

The last thing is what makes the trick work.  We can get rid of the denominator in $\frac{a + bi}{c + di}$ 
by multiplying top and bottom by the the conjugate of the denominator, $(c - di)$

Using the trick, write a formula in the form $x + yi$ for $\frac{a + bi}{c + di}$.

An amazing fact about the complex numbers is that they are _algebraically closed_.  That means that any polynomial equation that you can write with complex coefficients can be solved.  For example, $x^2 = -1$ has two solutions, $x = \pm i$.  What is amazing is that by just adding the solution to that equation and defining arithmetic operations as above, we end up being able to solve *any* polynomial equation. Actually, the statement is even stronger than that:

For every complex polynomial $p(z) = a_nz^n + a_n{-1}z^{n-1} + ... + a_0$ where $a_0, ..., a_n$ are complex coefficients, there are complex roots $r_0, ..., r_{n-1}$ such that $p(z) = (z - r_0)(z - r_1)...(z - r_{n-1})$. Every polynomial can be fully factored.  The $r_i$ are not necessarily distinct.  For example, consider

$p(z) = z^2 -2z + 1 = (z - i)(z - i)$

In that case $r_0 = r_1 = i$.

When a polynomial can be factored like that into a product of $(z - r)$ terms, where the $r$'s come from a set $A$ of some kind, we say that the polynomial _splits over A_.  So the amazing fact is that every polynomial with complex coefficients splits over $\mathbb{C}$. This obviously means that all polynomials with real coefficients also split over $\mathbb{C}$.  It can be shown that $\mathbb{C}$ is minimal among extensions of $\mathbb{R}$ with this property, so we say the $\mathbb{C}$ is the _algebraic closure_ of $\mathbb{R}$.

Use the $sin$ and $cos$ angle addition formulas to prove that for all complex numbers $z$ and $w$, $arg(zw) = arg(z) + arg(w)$

What is the relation between $|zw|$ , $|z|$ and $|w|$? Prove it.

The amazing fact above about algebraic closure means that for every $n>0$, the complex polynomial $p(z) = z^n - 1$ can be factored completely like so:

$z^n - 1 = (z - r_0)(z - r_1)...(z - r_{n-1})$

The $r_i$ are called the _complex nth roots of unity_ because they satisfy $r^n = 1$.

Find the 4th roots of unity.

## Complex functions
Complex functions are just functions with domain $\mathbb{C}$ and range a subset of $\mathbb{C}$.  When the range is contained in the real numbers, we call them _real-valued_ complex functions.  The function $f(z) = |z|$ is an example of a real-valued complex function.  We write $f: \mathbb{C} \to \mathbb{C}$ to indicate that $f$ is a complex function.

Graphing complex functions is not really possible.  To draw a graph that gives the full picture would require four dimensions, which we can't do. What can be informative is to graph just the real or imaginary parts of the function in on a 3D plot where the domain is shown as the base and the graph of the real or imaginary part is a surface. There are other ways to use colors and other means to illustrate the behavior of complex functions that we will revisit later.

## Iterated function systems

## Complex trigonometric functions
