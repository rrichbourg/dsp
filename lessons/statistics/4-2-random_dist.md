[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)

` pmf = thinkstats2.Pmf(np.random.random(1000), label='np_random')`

`thinkplot.Pmf(pmf, linewidth=0.1)`

`thinkplot.Config(xlabel='random numbers', ylabel='PMF')`

In the PMF it looks like some numbers are generated more frequently than others as indicated by the thickness of the bars shown. All of them have the same probabilities though. 

`cdf = thinkstats2.Cdf(np.random.random(1000), label='np_random')`

`thinkplot.Cdf(cdf)`

`thinkplot.Config(xlabel='random numbers', ylabel='CDF')`

On the CDF it looks like a pretty straight diagonal line, which means each random number generated increases the CDF by a steady/constant increment because it is a uniform distribution. 
