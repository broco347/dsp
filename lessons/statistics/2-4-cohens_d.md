[Think Stats Chapter 2 Exercise 4](http://greenteapress.com/thinkstats2/html/thinkstats2003.html#toc24) (Cohen's d)

#### Question:
Using the variable totalwgt_lb, investigate whether first babies are lighter or heavier than others. Compute Cohen’s d to quantify the difference between the groups. How does it compare to the difference in pregnancy length?

#### Code:
CohenEffectSize(firsts.totalwgt_lb, others.totalwgt_lb)  
CohenEffectSize(firsts.prglngth, others.prglngth)  

#### Results:
-0.088672927072602  
0.028879044654449883  

#### Response:
Unlike pregnancy length, the effect size of birthorder on birthweight is negative, meaning that the mean weight of first babies is smaller than that of other children. Though the effect size birthorder on birthweight is stronger than that of pregnancy length (-0.09 vs 0.03, respectively) it is still considered relatively small.
