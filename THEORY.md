# Theory

📘  THEORY

🔷 1.What is Statistical Distributions?

A statistical distribution shows how data values are spread or distributed.
It describes the probability of different outcomes of a random variable.
Examples include normal, binomial, and Poisson distributions.

    
🔷 2.What is a Q-Q Plot and why is it used?

A Q-Q (Quantile-Quantile) plot compares two distributions.
It helps check if data follows a normal distribution.
If points lie on a straight line, distributions are similar.

    
🔷 3.. Difference between Discrete and Continuous Distributions

Discrete distributions deal with countable values (e.g., 0,1,2).
Continuous distributions deal with infinite values in a range.
Discrete uses PMF, while continuous uses PDF.


🔷 4.What is Bernoulli Distribution?

It is a distribution with only two outcomes: success or failure.
Each trial has probability 
𝑝
p for success.
Example: coin toss (Head or Tail).

    
🔷 5.What is Binomial Distribution?

It gives probability of successes in multiple trials.
Each trial is independent with same probability 𝑝
Example: number of heads in 10 coin tosses. 


🔷 6. Explain Log-Normal Distribution

A variable is log-normal if its logarithm is normally distributed.
It is used for positive-valued data like income or stock prices.
The distribution is skewed to the right.


🔷 7.Explain Power Law Distribution
    
It shows that small values are common and large values are rare.
Follows relation: 
𝑃(𝑥)∝𝑥−𝑘P(x)∝x−k.
Used in networks, wealth distribution, etc. 

    
🔷 8.What is Box-Cox Transform?
    
It is a transformation used to make data normal.
It stabilizes variance and improves model performance.
Common in regression analysis.

    
🔷 9.Explain Poisson Distribution with an example
    
It models number of events in fixed time/space.
Events occur independently at a constant rate.
Example: number of calls received in an hour.

    
🔷 10.What is Z-score Probability?
    
Z-score measures how far a value is from mean in standard deviations.
It is used in normal distribution.
Helps find probability using Z-tables. 

    
🔷 11.differentiate probability density function (pdf) and cumulative distribution function (cdf)
    
PDF shows probability density at a point, while CDF gives cumulative probability up to that point.
CDF is integral of PDF, and PDF is derivative of CDF.
CDF ranges from 0 to 1, while total area under PDF is 1.

🔷  Conclusion 

Transaction data is right-skewed

Q-Q plot shows data is not normal

Log-normal distribution fits best

Power law explains extreme high values

High-value transactions (>₹5000) are rare

This helps in fraud detection and financial decision-making