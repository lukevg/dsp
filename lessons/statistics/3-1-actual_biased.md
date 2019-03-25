[Think Stats Chapter 3 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2004.html#toc31) (actual vs. biased)

##### Actual distribution:

resp = nsfg.ReadFemResp()

pmf = thinkstats2.Pmf(resp.numkdhh, label='numkdhh')

thinkplot.Pmf(pmf)

thinkplot.Config(xlabel='Number of children', ylabel='PMF')


pmf.Mean() = 1.0242051550438309

###### Biased distribution:

biased = BiasPmf(pmf, label='biased')

thinkplot.PrePlot(2)

thinkplot.Pmfs([pmf, biased])

thinkplot.Config(xlabel='Number of children', ylabel='PMF')

biased.Mean() = 2.4036791006642821

This shows that the biased distribution we would see if we surveyed the children
and asked them how many children under 18 (including themselves) are in
their household is more than twice the actual mean of children per household of just over 1.
