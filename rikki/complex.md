# Complex Numbers
## Definition
A complex number is a number with two parts: a _real_ part and an _imaginary_ part.

We often write complex numbers $z$ in the form $z = a + bi$ where $a$ and $b$ are
real numbers and $i$ is the "imaginary unit", $\sqrt{-1}$.

We visualize complex numbers as points in the _complex plane_.  

The complex plane has the real line as its x axis and the imaginary dimension on the y axis.
The complex number $x +yi$ corresponds to the point $(x,y)$.

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

Multiplication uses the distributed law:

$(a + bi)(c + di) = ac + adi + bci + bdi^2 = (ac - bd) + (ad + bc)i$ 

($bdi^2 = -bd$ because $i^2 = -1$.)

For any complex number $z = x + yi$, $-z = -x - yi$ is the _additive inverse_ of $z$. Note that for all $z$, $z + -z = 0 + 0i$
We refer to $0 + 0i$ as zero.  Complex zero is also the _additive identity_ among complex numbers - i.e., $z + (0 + 0i) = z$ for all $z$.

Subtraction and divison are defined the same way we do with real numbers,

$z - w$ is the complex number that you have to add to $w$ to get $z$ so $w + (z - w ) = z$

Write the definition of complex subtraction that will make this work.

$(a + bi) - (c + di) = $???

To define complex division, we would like to express $\frac{a + bi}(c + di} in the form $x + yi$.  
To get to that form, we can use a trick to clear the denominator. The trick uses what we call the complex conjugation.

For a complex number $z = x + yi$, we define the _conjugate_, $conj(z)$ to be $x - yi$. So conjugation is just flipping the sign on the imaginary part of the number.  Graphically, this amounts to reflecting the point across the $x$ axis in the complex plane. 

Show that for all $z$
1.  $arg(conj(z)) = -arg(z).$
2.  $|z| = $|conj(z)|$
3.  $z \mdot conj(z) = $|z|^2$

The last thing is what makes the trick work.  We can get rid of the denominator in $\frac{a + bi}(c + di} 
by multiplying top and bottom by the the conjugate of the denominator, $(c - di)$

Using the trick, write a formula in the form $a + bi$ for $\frac{a + bi}(c + di}.







