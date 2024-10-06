# Trigonometric functions
## Pythagorean theorem

<img src=https://miro.medium.com/v2/resize:fit:923/1*SsN2DG__Z5DyOI0uf7hbwQ.png width=400>

Given a right triangle with altitude $a$, base $b$ and hypotenuse length $c$, we have

$a^2 + b^2 = c^2$

Use the Pythagorean theorem to write an expression for the distance between the two points

$(x_1, y_1)$ and $(x_2,y_2)$

The (Euclidean, metric) *norm* of a point $(x, y)$ in the plane (what we call $\mathbb{R}^2$) is its distance from the origin.
Use the Pythgoran theorem to write an expression for the norm of $(x,y)$.

## Definition of sine and cosine
The *unit circle* is the circle of radius $1$ centered at the origin in $\mathbb{R}^2$.  
![image](https://www.mathsisfun.com/geometry/images/unit-circle.svg)

The circumpherence of the unit circle is $2\pi$. 

The $sin$ and $cos$ functions are defined by considering points on the unit circle as functions of the length of the arc leading to them.

![image](https://d18l82el6cdm1i.cloudfront.net/uploads/hZzzziI3DV-sin-cos01.gif)

For example, $1/4$ of the way around the circle is $1/4$ of $2\pi$ arc length or $\pi/2$. 

One quarter of the way around the circle counter-clockwise, starting from $(0,1)$ puts us at the point $(0, 1)$ - the top point of the circle.
That means $cos(\pi/2) = 0$ and $sin(\pi/2) = 1$  

The unit of measure when we measure arc length around the unit circle is *radians*.  As arc-length continues past $2\pi$, the values repeat, so

$sin(x \pm 2\pi) = sin(x)$ for all $x$ and same for $cos$. 

## Special values
 1. Find $$cos(\pi/4)$$ using the fact that when $x$ is $\pi/4$, $x$, the angle is 45 degrees, so $sin(x)$ and $cos(x)$ must be the same value.
 2. Find $sin$ and $cos$ for all multiples of $pi/4$ up to $2\pi$.
 3. Use 30-60-90 triangle to fill in values for all multiples of $$\pi/6$$
 <img src=https://lh4.googleusercontent.com/proxy/FwbSjQ5oGYt4QGbOzSuIOWJ8EX5XGbM45ss6BMCF1TSNTbBcXgT5Lo-Q87bBHYnovSB-9fh9QAuAXVLPBAo8x6h7nkONLoTMVc5Bc-Zbz69j4_oY8vn2L9EQUv-qgHUyAx0 width = 300>

## Definition using triangles
The $sin$ and $cos$ functions can also be defined using right triangles. Consider the right triangle

![image](https://github.com/user-attachments/assets/93e1bc79-481e-4a7b-96e9-14a188fc3f34)

Let $o$ be the length of the side labeled "opposite", $a$ be the length of the "adjacent" side and $h$ the length of the hypotenuse. Then

$sin(\theta) = o / h$

$cos(\theta) = a / h$

If h = 1, then these values are obviously the same as the definition in terms of the unit circle.  If $h$ is different from $1$, then dividing by h gives dimentions of a similar triangle with hypotenuse 1.

## Graphs of sine and cosine
 1. Make tables for the sin and cos functions for the special values (multiples of $\pi/4$ and $\pi/6$)
 2. Graph sin and cos together in one coordinate plane
 3. Describe the relationship betwen the two curves
 4. A function $f : \mathbb{R} \to \mathbb{R}$ is *strictly increasing* over the interval $[a,b]$ if for all $x_1$ and $x_2$ in $[a,b]$, if $x_1 < x_2$ then $f(x_1) < f(x_2)$. Find the subintervals within $[0,2\pi]$ over with the sin is strictly increasing.  Then do the same for the cosine.
 5. Fill in the blank: If the cos is ____ then the sin is increasing.  Explain why this is true.
 6. Select one: If the rate of change of cos is increasing at $x$ then $cos(x)$ is [ ] positive [ ] negative.  Explain.

## Trigonometric identities
One can create an entire HS class deriving and playing with formulas relating values of the sin and cos functions. Most are rarely used.  The proofs tend to be geometric arguments that are not terribly interesting. Here are two that are used quite a bit. They are called the _angle addition forumulas_ for $sin$ and $cos$.

$cos(a + b) = cos(a) cos(b) - sin(a) sin(b)$

$sin(a + b) = sin(a) cos(b) + cos(a) sin(b)$

By examining points on the unit circle, verify that the angle addition formulas hold for all multiples of $\pi/4$.

