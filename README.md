## Exploring Concepts taught in AI2200 :)

Visualizing tails and seeing how the choice of noise distribution affects:

- Empirical loss
- Number of samples required to be confident about the expected loss

I used synthetic linear regression data to compare:

- Gaussian noise (light tails) 
- Laplace noise (heavy tails)

and also how Hoeffding's inequality and Bernstein's inequality tell us the sample size needed to ensure our empirical loss doesn’t deviate too much from the true mean (which we don’t actually know :P).
It’s one of the neat ways to see how heavier-tailed noise like Laplace can make losses larger and increase variance, while Gaussian noise behaves “nicely” with lighter tails :)
