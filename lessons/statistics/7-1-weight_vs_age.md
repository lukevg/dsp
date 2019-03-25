[Think Stats Chapter 7 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2008.html#toc70) (weight vs. age)



ages = live.agepreg

weights = live.totalwgt_lb

print(Corr(ages, weights)) = 0.0688339703541

print(SpearmanCorr(ages, weights)) = 0.0946100410966

import matplotlib.pyplot as plt
plt.scatter(ages, weights, s=20, c='g', alpha=0.2)
plt.show()

There is almost no relationship between birthweight and mother's age, as Pearson's and Spearman's Correlation are both below 0.1. The scatterplot reflects these results, although observations are densely clustered so it is difficult to draw further conclusions.


