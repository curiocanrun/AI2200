### I explored a few concepts taught in the AI2200 course through code :)

how the choice of noise distribution affects:

- Gaussian noise (light tails)
- Laplace noise (heavy tails)

and also looked at how Hoeffding's inequality and Bernstein's inequality bound the sample size needed to keep the empirical loss from straying too far from the true mean (which we don’t actually know :P).


It’s one of the neat ways to see how heavier-tailed noise like Laplace can make the losses larger and more variable, while Gaussian noise behaves “nicely” with its lighter tails :)
