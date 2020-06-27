[Think Stats Chapter 5 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2006.html#toc50) (blue men)

`import scipy.stats`

`mu = 178`
`sigma = 7.7`
`dist = scipy.stats.norm(loc=mu, scale=sigma)`

`dist.cdf(185.42)-dist.cdf(177.8)`

0.3427468376314737

34.27% of men are between 5'10" and 6'1"
