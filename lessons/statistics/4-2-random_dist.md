[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)

other_wgt = others.totalwgt_lb

other_wgt_dropna = other_wgt.dropna()

print('Others', len(other_wgt), len(other_wgt_dropna))

def PercentileRank(scores, your_score):
    count = 0
    for score in scores:
        if score <= your_score:
            count += 1

    percentile_rank = 100.0 * count / len(scores)
    return percentile_rank

other_cdf.PercentileRank(9.4) = 95.14438502673796

My birthweight of 9.4 lbs is in the 95th percentile for babies who are not first-born. I did not call my mother to apologize, as I have previously apologized for being such a massive baby.
