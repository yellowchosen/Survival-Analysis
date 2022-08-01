# Negative Binomial Distribution

**Definition:** In probability theory and statistics, the negative binomial distribution is a discrete probability distribution that models the number of successes in a sequence of independent and identically distributed Bernoulli trials before a specified (non-random) number of failures (denoted r) occur.

* r is number of successes
* k is the number of failures
* p is the probability of success

The probability mass function of the negative binomial distribution is:

$$ f(k;r,p) = Pr(X = k) =\frac{(k+r-1)!}{(r-1)!(k)!}(1-p)^rp^k $$


# Negative Binomial Regression
In survival analysis, we often taken NB regression as a non-survival approach for recurrent event analysis, and the NB regression analyzes the recurrent events as count data — irrespective of when the events occurred

So based on this property, the NB regression is a popular approach for analyzing frequency of exacerbations in asthma and COPD studies.
Because it can yield easily interpreted estimates of **event rates** and **treatment effects** and can account for event rate heterogeneity between patients.

* Event rates: $\frac{event}{total}$
* Treatment effects: frequency of exacerbation
