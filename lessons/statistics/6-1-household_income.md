[Think Stats Chapter 6 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2007.html#toc60) (household income)

log_sample = InterpolateSample(income_df, log_upper=6.0)

sample = np.power(10, log_sample)

Mean(sample) = 74278.707531187392

Median(sample) = 51226.454478940461

Skewness(sample) = 1.054840012109306

PearsonMedianSkewness(sample) = 0.26436733816180391

cdf.Prob(Mean(sample)) = 0.66000587956687196

About 66% of the polulation makes less money than the mean income of $74278

The result is based on the assumption that maximum income is $1 million, while maximium income is much, much higher in reality. We would a more accurate measure of sknewness if there was more data included about incomes higher than the upper bound of $1 million. 
