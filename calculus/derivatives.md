# Derivatives

## Rates of change
One of the most useful concepts in calculus is the rate of change of a function.  By looking at the graph of a function, we can see where it is increasing, decreasing or constant, but we don't yet have a way to tell *how much* a function is increasing or decreasing at different points.  Consider the graph of the function $f(x) = x^3$ below. The function is obviously increasing everywhere, except maybe at $0$ where it looks like it is kind of stalling. Down at the point $(-2, -8)$ the graph looks steeper than it is at $(-1, -1)$.  The same seems to hold at $(1, 1)$ and $(2, 8)$ - the graph is steeper at the second point.  So it looks like for negative values, as $x$ increases, the graph is less steep but for positive values, as $x$ increases, the graph is more steep. 

![image](https://search-static.byjusweb.com/question-images/toppr_ext/questions/1239085_1166950_ans_d9de59e2cce140baa2cc827a40e76ebe.PNG)

Just looking at the graph and plotting points doesn't give us a precise definition of what "steepness" means in the sense that we have been using that word. 

When you think about it, it's not even obvious exactly what the rate of change means at a point. "How fast is the function increasing/decreasing?"  Generally, when we talk about rates of change, we refer to some kind of interval, not a point.  For example, when we say a car is traveling at 80 miles per hour, we mean that if it keeps going at that same speed it will travel 80 miles in an hour.

Give three more examples of rates of change in physical or social systems. Try to determine how these rates are defined and computed.

## Average rates of change

Look carefully again at the the point $(1,1)$ on the graph of the function $f(x) = x^3$ above.  Clearly the functio is increasing at that point.  If you move a little to the right along the $x$ axis, the value of $f(x)$ increases.  If you go all the way to $x = 2$, the value goes all the way to up to $8$.  The average rate of change of the function over the interval $[1,2]$ is $(8 - 1) / (2 - 1) = 7.$ That is the slope of the line segment that connects the two points $(1,1)$ and $(2,8).$  We call that line the *secant line* because it connects points along the curve of the graph.  Let's now look at $x = 1.5.$  The value of the function at that point is ${1.5}^3 = 3.375$ so the average rate of change over the interval $[1,1.5]$ is $(3.375 - 1) / (1.5 - 1) = 4.75$.

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
| .25 |  |
|  .1  |  |
| .05 |  |

It is comforting to see that these values are converging on the same limit.  Why does that give us more confidence in our estimate of the rate of change of the function at $x = 1$?

Use the approach above to find the rate of change of the $sin$ function at the points $\pi / 4$ and $\pi.$

Find an interval of positive length over which the average rate of change of the $sin$ function is 0.

## Limit concept

## Derivative as limit of discrete change

## Why it makes sense that cos is derivative of sin.
