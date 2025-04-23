# Derivatives

## Rates of change
One of the most useful concepts in calculus is the rate of change of a function.  By looking at the graph of a function, we can see where it is increasing, decreasing or constant, but we don't yet have a way to tell *how much* a function is increasing or decreasing at different points.  Consider the graph of the function $f(x) = x^3$ below. The function is obviously increasing everywhere, except maybe at $0$ where it looks like it is kind of stalling. Down at the point $(-2, -8)$ the graph looks steeper than it is at $(-1, -1)$.  The same seems to hold at $(1, 1)$ and $(2, 8)$ - the graph is steeper at the second point.  So it looks like for negative values, as $x$ increases, the graph is less steep but for positive values, as $x$ increases, the graph is more steep. 

![image](https://briannacorrigan.weebly.com/uploads/4/7/6/3/47631121/6231487.gif?250)

Just looking at the graph and plotting points doesn't give us a precise definition of what "steepness" means in the sense that we have been using that word. 

When you think about it, it's not even obvious exactly what the rate of change means at a point. "How fast is the function increasing/decreasing?"  Generally, when we talk about rates of change, we refer to some kind of interval, not a point.  For example, when we say a car is traveling at 80 miles per hour, we mean that if it keeps going at that same speed it will travel 80 miles in an hour.

Give three more examples of rates of change in physical or social systems. Try to determine how these rates are defined and computed.

## Average rates of change

Look carefully again at the the point $(1,1)$ on the graph of the function $f(x) = x^3$ above.  Clearly the function is increasing at that point.  If you move a little to the right along the $x$ axis, the value of $f(x)$ increases.  If you go all the way to $x = 2$, the value goes all the way to up to $8$.  The average rate of change of the function over the interval $[1,2]$ is $(8 - 1) / (2 - 1) = 7.$ That is the slope of the line segment that connects the two points $(1,1)$ and $(2,8).$  We call that line the *secant line* because it connects points along the curve of the graph.  Let's now look at $x = 1.5.$  The value of the function at that point is ${1.5}^3 = 3.375$ so the average rate of change over the interval $[1,1.5]$ is $(3.375 - 1) / (1.5 - 1) = 4.75$.

Fill in the following table:

| $x$    | ($f(x) - f(1)) / (x - 1 )$|
| -------- | ------- |
| 2        | 7   |
|1.5  | 4.75 |
| 1.25 |  |
| 1.1  |  |
| 1.05 |  |

What value does it look like these values are converging to?

Explain why it makes sense that this value is the rate of change of the function at $1$.

Explain how it makes sense that as the $x$ value gets closer and closer to $1$ the secant line connecting the two points used in the average rate of change computation approaches a line tangent to the curve.

Make another table like the one above, but looking at points to the left of $x = 1$

| $x$    | ($f(x) - f(1)) / (x - 1 )$|
| -------- | ------- |
| 0        |   |
| .5  | |
| .75 |  |
|  .9  |  |
| .95 |  |

It is comforting to see that these values are converging on the same limit.  Why does that give us more confidence in our estimate of the rate of change of the function at $x = 1$?

Use the approach above to find the rate of change of the $sin$ function at the points $\pi / 4$ and $\pi.$  Use a calculator to compute the values of the function.  Make sure that the calculator is configured to take inputs in radians.  Here is one of many [online trig function calculators](https://www.calculatorsoup.com/calculators/trigonometry/trigonometricfunctions.php).

Find an interval of positive length over which the average rate of change of the $sin$ function is 0.

## Limit concept

We write $\mathop {\lim }\limits_{x \to a} f(x) = b$ to mean that as $x$ approaches $a$ (from either direction), the value of $f(x)$ converges on $b$.

For example, 

$\mathop {\lim }\limits_{x \to 0} x^2 = 0$ 

$\lim_{x \to \pi} sin(x) = 0$ 

$\mathop {\lim }\limits_{x \to 0} cos(x) = 1$ 

Evaluate the following limits:

$\mathop {\lim }\limits_{x \to \infty} \frac {x + 1}{x}$ 

$\mathop {\lim }\limits_{x \to \infty} \frac {1}{x}$ 

$\mathop {\lim }\limits_{x \to 0} \frac {sin(x)}{x}$ 


## Derivative as limit of average change

The derivative of a function at a point is the rate of change of the function at that point.

We saw above that for $x^3$ and $sin(x)$ we can define that rate of change to be the value that the average rate of change of the function converges to as you consider smaller and smaller intervals around the point. This is the slope of the tangent line to the graph of the function at the point. That is how we define the derivative.

Formally, 

$\frac{d}{{dx}}f(x) = \mathop {\lim }\limits_{\delta \to 0} \frac{{f\left( {x + \delta } \right) - f\left(x\right)}}{\delta }$

Note that the deriviative is itself a function. When the derivative limit exists at a point, we say that the function is *differentiable* at that point.  We sometimes use the notation $f'$ for the derivative of $f$.  The process of finding $f'$ when given $f$ is called *differentiation*.

Compute average rates of change at a few points to confirm that it looks like

if $f(x) = x^2$ then $f' (x) = 2x$

if $f(x) = sin(x)$ then $f' (x) = cos(x)$

### Canonical example - velocity and distance
Consider an object moving along the positive real axis.  Assume that it starts at $0$ at time $t = 0$ and at any time $t>0$ its position measured in feet is $d(t).$ 

Suppose that the object is moving at a constant velocity of $5$ feet per second.  

Write a formula for $d(t)$

Draw the graph of $d(t)$

Find $d' (1)$ 

How can you tell from the shape of the graph that $d' (t)$ is the same value as above for all $t>0$?

It looks like $d' (t) = 5$ for all $t$ so the derivative of distance is velocity in this example. This is no accident.  Whenever the distance function is differentiable, its derivative is always the velocity function.  

Note how this makes sense in this case:

Velocity is the rate of change of distance over time.  Constant velocity of $5$ feet per second means that the rate of change of distance always takes the value $5$.  

Suppose that Alice climbs a trail with a bone in her mouth to get to an outropping at the top that has a sheer drop of 400 ft to a canyon floor below.  Fortunately, Alice stops at the edge, but she drops her bone.

Assuming that the bone just drops out of her mouth and ignoring wind resistance, it will fall according to the laws of gravity, which means that it will accelerate by $32$ ft/second every second.  So after $1$ second it will be falling at $32$ ft/sec, after $2$ seconds it will be going down $64$ ft/sec and so on, constantly accelerating until it hits the canyon floor.

In this case, the distance function is a little more complicated.  Velocity is $d' (t) = v(t) = 32t$.  To find $d(t)$ we have to somehow find the function whose derivative $v(t)$ is, i.e., its "anti-derivative."  We don't have the tools to do that just yet, but we will see later that if we set $d(t) = \frac {1}{2} 32 t^2 = 16t^2$ then $v(t) = d' (t) = 32t$.

How long will it take Alice's bone to reach the canyon floor?

Imagine now that Alice gets abducted by (nice,vegan) aliens and she ends up doing the same thing at a similar place on their planet where there is less gravity so the acceleration due to gravity is only 10 ft/sec/sec.  How long does the bone take now?

Note that acceleration is the derivative of velocity which makes it the derivative of the derivative of distance.  We call that the *second* derivative - the rate of change of the rate of change of the function.

It's worth thinking about this basic example over and over again because it illustrates the derivative concept in a simple, physical way:

velocity is the rate of change of distance - $v(t) = d' (t)$

acceleration is the rate of change of velocity - $a(t) = v' (t) = d'' (t)$

In the first example, velocity was constant, so $a(t) = 0$ everywhere.  In the Alice adventure examples, $a(t)$ is a non-zero constant.


## Why it makes sense that cos is derivative of sin

Make a table of values of sin and cos for $\pi/4$ splits

Add a column for whether sin is increasing, decreasing or at an min or max value.

Find two points on the graph where the derivative (slope of the tangent) looks like it should be at is maximum. What is the value of the cosine function at these points.

Repeat above for points where the derivative looks like it should be the most negative that it can be. Observe the value of the cosine function at these points.

Finally, look at points where the slope of the sin function graph looks like it is 0 (min or max points).  What is the value of the cosine function at these points?

## Formal definition of limit

When we looked at the average rate of change of $f(x) = x^3$ for different $x$ values above, we saw the average approached a limiting value when the average was taken over smaller and smaller intervals around $x$. In particular, we saw that for $x$ equals $1$, the limiting value is $3$.

We need a rigorous defintion of what it means for $f(x)$ to approach a fixed value $L$ as $x$ approaches a value $a$.   

To get a better idea what we are shooting for here it is a good idea to look at a "non-example", i.e. a function and a point where the average rate of change does not converge to number $L$. It's important to learn early and always keep in mind that derivatives often don't exist (there is no fixed limit).  When that happens, we say that that the function is *not differentiable* at the point where the limit "fails to converge."

Consider the function $f(x) = |x|.$  Draw its graph.  From looking at the graph, what does it look like the rate of change of the function is at $x = 1, x = 2, x =-1$?  

Now consider $x = 0$.  What about that point?  If we look at points to the right of $0$, the average rate of change between the function at $0$ and those points is always $1$.  Its graph for $x \ge 0$ is the line $y=x.$  But approaching $0$ from the other side, the average rate of change is always $-1$ because the graph on negative side of the real axis is the line $y=-x$.

In the case above, we say the limit *does not exist*.  So formally

$\mathop {\lim }\limits_{h \to 0} \frac {|x + h| - |x|} {h}$

does not exist.

The problem above is that there are two different numbers that the derivative expression can take arbitrarily close to $x=0$.  The limit definition says that can't happen - i.e., however close you want to force the limit expression to be to $L$, you can force that to be true if you force $h$ to be sufficiently close to $0$.  So we define $\mathop {\lim }\limits_{x \to a} = L$ to mean that however close we want to force $f(x)$ to be to $L$, there is a tolerance that we can set on $x$ so that if $x$ is within that tolerance of $a$, then $f(x)$ will be that close to $L.$

### Limit Definition
$\mathop {\lim }\limits_{x \to a} = L$ means that for every real number $\epsilon > 0$, there is a real number $\delta > 0$ such that for all $x$ such that $|x - a| < \delta$ we have $|f(x) - L| < \epsilon$.

### Example Limits

Suppose that $f(x) = 2x$.  What is $\mathop {\lim }\limits_{x \to 1} f(x)$?  If you make a little table of values of the $f$ near $x=1$ it's easy to see that the value of this limit is $f(1) = 2$.  To show that the limit definition is satisfied here we have to show that for any $\epsilon>0$ there is a $\delta > 0$ such that if $x$ is within $\delta$ of $1$ then $f(x)$ will be within $\epsilon$ of $2$. So suppose that $\epsilon > 0$ is given.  We need to find $\delta > 0$ so that if $|x - 1| < \delta$ then $|2x - 2| < \epsilon$.  Since $|2x - 2| = |2(x - 1)| = 2|x - 1|$ if we just use $\delta = \epsilon / 2$ then $|x - 1| < \delta$ means 2|x - 1|$ < 2\delta = \epsilon$.

Now lets look at $f(x) = x^2$ at the point $x = 0.$  What is $\mathop {\lim }\limits_{x \to 0} f(x)$?  A good guess is the value of the function at the point, which is correct in this case

${\lim }\limits_{x \to 0} f(x) = 0$

To prove that this value is correct, let $\epsilon$ be an arbitrary positive real number.  We need to find a positive $\delta$ such that if $|x - 0| < \delta$, we must have $|x^2 - 0| < \epsilon$. Without loss of generality, we may assume that $\epsilon$ is less than $1$ (why?).  In this case, we can just use $\delta = \epsilon.$  As long as $|x - 0| = |x| < \delta$, then $|x^2 - 0| = |x^2| = |x|^2 < \delta ^ 2 = \epsilon ^ 2 < \epsilon$ (since $\epsilon < 1$).

Prove that ${\lim }\limits_{x \to 1} x + 1 = 2$

Prove that ${\lim }\limits_{x \to 0} x^2 + 2x + 1 = 1$

It's a little awkward that we have always say, "for every $\epsilon$ there is a $\delta$...".  Show why we can't dispense with $\delta$ to just say "for every real number $\epsilon > 0$, for all $x$ such that $|x - a| < \epsilon$ we have $|f(x) - L| < \epsilon$".  I am asking you to find a function $f$ and a value $a$ where the value of $f(x)$ converges to a limit $L$ as $x$ approaches $a$, but for some $\epsilon$, keeping $x$ within $\epsilon$ of $a$ does not keep $f(x)$ within $\epsilon$ of $f(a)$.

### Continuity Definition
The function $f: \mathbb{R} \to \mathbb{R}$ is *continuous* at the point $a$ if  ${\lim }\limits_{x \to a} f(x) = f(a)$

Continuity means that there are no "holes" in the graph of the function and it does not escape to positive or negative infinity around the point.  To say that ${\lim }\limits_{x \to a} f(x) = f(a)$ means that as $x$ approaches $a$ from either side, the values of $f(x)$ converge on the value of $f$ at $x=a$.  

Show that $f(x) = |x|$ is continuous at $x = 0$.  We saw above that $f$ is not differentiable there, but it is continuous at this point.

Consider the function $f(x) = x$ if $x < 0$ or $x + 1$ if $x \ge 0$.  Show that $f$ is not continuous at $0$.  Is $f$ continuous at other points?  Where is $f$ differentiable?

## Examples

