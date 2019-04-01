[Think Stats Chapter 6 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2007.html#toc60) (household income)

**The following represents my original solution:**
>> Bayes' Theorem: P(H|E) = P(E|H) P(H)/ P(E)  
>> With the appropriate information plugged in, our problem looks like this:  
>> P(Elvis is identical twin| Elvis is twin) = P(Elvis is twin| Elvis is identical twin) * P(Elvis is identical twin)/ P(Elvis is twin)  
>> This translates to: P(Elvis is identical | Elvis is twin) = 1 * 0.003/ .011**  
>> Thus, given that Elvis was a twin, the probability of him being an identical twin is 0.2727, or 27.27%.  
>> ** We get the probability that Elvis is a twin by adding the probabilities of being a fraternal and an identical twin within the larger population.

**UPDATE:**
>> Upon looking at solutions online, I found that I did not take the sex of Elvis' twin into consideration, which makes the probability of Elvis being an identical twin a bit larger, given that identical twins must be the same sex while the sex of fraternal twins may vary. In trying to update my solution, I came up with the following:  
>> P(Elvis is identical twin | Twin was male) = P(Twin was male| Elvis is identical twin) * P(Elvis is identical twin)/ P(Twin was male)  
>> However, when plugging in the numbers, I am left where I started:  
>> P(Elvis is identical twin | Twin was male) =  1 * .2727 / 1 = .2727  
>> Note: I placed a 1 in the denominator, because we are given that Elvis' twin is the same sex. However, in adjusting the denominator to reflect the probability of Elvis' twin being male (~ .5), I am left with:  
>> P(Elvis is identical twin | Twin was male) =  1 * .2727 / .5 = .5454  
>> This solution seems a bit high to me, though I am not sure where my caluculations may have gone wrong. 