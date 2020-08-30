# GENERATING SIMPLE DISTRIBUTIONS - monopixel image (GAN)
To fully understand a how GANs work, we should start by modeling the simplest situation: generating an univariate distribution.
We can think of it as generating an grey scale image with just one pixel. 
Suppose the real distribution is 
$$ N(0,1) $$

The goal in this case is to have a generator that outpus values in $\mathbb{R}$ according to real data distribution, i.e., the majority of the generators output fall in a neighbourhood of 0.
