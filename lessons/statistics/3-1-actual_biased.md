[Think Stats Chapter 3 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2004.html#toc31) (actual vs. biased)

resp = nsfg.ReadFemResp()


pmf = thinkstats2.Pmf(resp.numkdhh, label='numkdhh')

  thinkplot.Pmf(pmf)

  thinkplot.Config(xlabel='Num_Children_U18_household', ylabel='PMF')


bias_pmf = BiasPmf(pmf, label='bias')

  thinkplot.Pmf(bias_pmf)

  thinkplot.Config(xlabel='Bias_Num_Children_U18_household', ylabel='PMF')


pmf.Mean()

  1.024205155043831

bias_pmf.Mean()

  2.403679100664282
