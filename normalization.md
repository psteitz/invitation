# Normalizing data for index computation
## Motivation
People often use combinations of numberic values of some kind to create indexes or "overall" scores.  
Typically, weigths are assigned to the constituent scores with the intent that a higher weight means more influence on the overall score.
For example, to get a summary measure of business unit performance, an executive might compute an index of revenue and gross profit, with equal weights.
Done naively, just setting performance = .5 revenue + .5 profit, the result will actually end up weighing revenue more, because revenue values
are larger than profit values.
