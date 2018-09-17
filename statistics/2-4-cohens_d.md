[Think Stats Chapter 2 Exercise 4](http://greenteapress.com/thinkstats2/html/thinkstats2003.html#toc24) (Cohen's d)
```
first_wgt.describe()  
count    4363.000000  
mean        7.201094  
std         1.420573  
min         0.125000  
25%         6.437500  
50%         7.312500  
75%         8.000000  
max        15.437500  
Name: totalwgt_lb, dtype: float64  

others_wgt.describe()  
count    4675.000000  
mean        7.325856  
std         1.394195  
min         0.562500  
25%         6.500000  
50%         7.375000  
75%         8.187500  
max        14.000000  
Name: totalwgt_lb, dtype: float64  

first_wgt.mean(), others_wgt.mean()  
(7.201094430437772, 7.325855614973262)  

CohenEffectSize(first_wgt, other_wgt)  
-0.088672927072602  
```
We can see that first babies are likely to be lighter than others, but the difference is not relevant  
Cohen's d of 0.089 represents that 54% of the 'others' babies are above the firsts babies weight mean  
Comparing to the difference in pregnancy length (Cohen's d of 0.029), neither values are relevant, concluding that being the first baby does not pose any effect to the child.  
