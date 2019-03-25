[Think Stats Chapter 5 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2006.html#toc50) (blue men)

import scipy.stats

mu = 178

sigma = 7.7

dist = scipy.stats.norm(loc=mu, scale=sigma)

5'10" = 177.8cm

6'1 = 185.4cm

low = dist.cdf(177.8)  = 0.48963902786483265

About 49% of population is below 5'10"

high = dist.cdf(185.4) = 0.83173371081078573

About 83% of population is below 6'1"

diff = high - low = 0.34209468294595308

Roughly 34.2% of the male population is within the height range for eligibility to join Blue Man Group
