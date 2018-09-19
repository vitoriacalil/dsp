[Think Stats Chapter 5 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2006.html#toc50) (blue men)

```python
import scipy.stats
mu = 178
sigma = 7.7
dist = scipy.stats.norm(loc=mu, scale=sigma)
dist.mean()
```
```python
# define Blue Man Group requirements
high = dist.cdf(185.4)
low = dist.cdf(177.8)
low, high, high-low
```
```
(0.48963902786483265, 0.8317337108107857, 0.3420946829459531)
```
34% of the population meets height requirements to be a member of BMG.
