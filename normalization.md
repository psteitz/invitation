# Normalizing data for index computation
## Motivation
People often use combinations of numberic values to create indexes or ratings. Typically, weigths are assigned to the constituent scores with the intent that a higher weight means more influence on the overall score.

The simplest model is to make the rating the sum of weights times the constituent score values.  Mathematically, if we let $x_0, ..., x_{n-1}$ be the scores
and $w_0, ..., w_{n-1}$ be the weights, then the rating is $r(x_0, ..., x_{n-1}) = \sum_{i=1}^{n-1} x_iw_i$

If the $x_i$ are not scaled the same way, the intent of the weighting may not be realized. Constituent scores with relatively larger values can end up dominating the ratings.  Here is a simple example showing what can go wrong.  Suppose that $n = 2$ and the two variables are both normally distributed (following bell-shaped curve) with mean $0$, but the first one has standard deviation $1$ while the second has standard deviation $3$. And suppose that we want them to have equal weight in the rating, so $w_0 = w_1 = 0.5$.  Consider the data in the following table:


| $x_0$ | $x_1$ | $r(x_0, x_1) = 0.5x_0 + 0.5x_1$ |
| ----- | ----- | ------------------------------- |
| 0 | 0 | 0 |
| 0 | 3 | 1.5 |
| 1 | 0 | 0.5 |
| 2 | 0 | 1.0 |

Starting with $x_0 = x_1 = 0$, if we increase $x_1$ by one standard deviation, the rating goes up by $1.5$ units.  If we make a similar change in $x_0$, the rating only increases by $.5$.  Even making a $2$ standard deviation change in $x_0$ makes a smaller difference in the score than a single standard deviation change in $x_1$. Clearly, $x_1$ has more de facto weight than $x_0$.  Another way to see this is to observe that in this case the random random variables that $x_0$ and $x_1$ come from satisfy the equation, $X_1 = 3X_0$, so when computing the rating, it's as though the $x_1$ values start with a 3-times larger weight.

## Normalization
To make sure that the weights do what we intend them to do, we need to get the data for the different variables into a common scale.  This process is called *normalization.* The best way to normalize variables depends on the distributions of the data and our objectives for the rating.  Here are some of the most common techniques.

### min-max proportional scaling
This technique forces all variables to be scaled between $0$ and $1$ by mapping values to how far along they are in the path from the mininmum to the maximum value for the variable.  Mathematically, suppose the the minumum for all values of $x_i$ is $min_i$ and the maximum is $max_i$, then the normalized value of a given value $x$ is $\frac{x - min_i}{max_i - min_i}$.  So the minumum value gets mapped to $0$ and the maximum value gets mapped to $1$ and all values between are mapped to the proportion of distance between the min and max that they represent.  This kind of mapping does get the scores to a common scale, but it does not normalize standard deviations and it can be distorted for variables the contain extreme values.  

### z-scores
This technique forces the scores to have the same expected values (means) and standard deviations, by taking each score and subtracting the mean of the variable that it comes from and dividing by its standard deviation.  So if $\mu$ is the mean of a variable and $\sigma$ is its standard deviation, the normalized value for $x$ is $\frac{x-\mu}{\sigma}$.  This achieves the objectives of making means and standard deviations the same, but it does not impose upper or lower bounds on the normalized scores and they end up centered at $0$ (so you get both positive and negative normalized scores).

### percentiles
This technique maps scores to percentiles computed among observed values for each variable.  The percentile score of a value is the percentage of all of the values that are less than or equal to the given value.  This results in scores ranging from $0$ to $100$.  It does not make means or standard deviations the same, but it does take into account how the values are distributed.

### binning
Here the range of values of each variable is divided into a fixed number of "bins".  The bin ranges for different variables may be different, but the same bin numbers are applied to each variable.  For example, scores might be divided into just three bins - small, medium, and given the binned scores $0, 1, 2$.  Using the same number of bins and bin scores across variables makes the scores comparable.  This technique does not make means or standard deviations the same and it requires that you maintain the bins.

### truncated, shifted and rescaled z-scores
The negative values and unbounded range of the z-score transformation makes ratings results non-intuitive for a lot of people, so what is sometimes done is to make the folllowing adjustments to the $z-score$
 1. Multiply by a constant, say $3$ (to spread out the scores)
 2. Shift the values so the mean is not 0 (add say 5)
 3. Truncate the values, pushing any remaining negative values (after the shift) to 0 and similarly top-coding to a maximum value (say 10)
This aligns the means and standard deviations and makes the ratings easier to work with, but it requires some fiddling to set up and, like binning, it must be maintained as the data changes.

