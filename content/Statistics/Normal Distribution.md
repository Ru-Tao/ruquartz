## Hypothesis testing with normal distribution.

>[!question]+ Example 1
>
>It is known that the lifetime, in years, of a ring-tailed aardvark in the wild has a mean of 13.3 and variance of 12.25. A sample of 50 randomly chosen ring-tailed aardvarks that had been kept in zoos had a mean lifetime of 12.48 years.
>
>Test at the 5% significance level, whether there is evidence that the ring-tailed aardvarks kept in zoos have a shorter life expectancy than in the wild.
>
>>[!todo]- Answer 
>>
>>- To begin we can establish we have the following
>>- A critical region of 5%
>>- A sample size of 50
>>- A sample mean of 12.48
>>- The null hypothesis, $H_0:\mu=13.3$
>>- The alternative hypothesis, $H_1:\mu<13.3$
>>- The mean,$\mu=13.3$ and the variance,$\sigma^2=12.25$
>>- With this we can create our basic normal distribution for all cases.
>>$$
>>X \sim  N(13.3, 12.25)
>>$$
>>- However as we have a sample size of 50 we have to find the distribution for within the 50. We can call this distribution $\bar{X}$.
>>
>>$$
>>\bar{X} \sim N(13.3,\frac{12.25}{50})
>>$$
>>
>>- As $\bar{X}$ is within the sample size of 50, we must divide our variance, $\sigma^2$, by 50.
>>- Using this distribution we can find the probability that $\bar{X}$ is under our mean taken from the sample size, being 12.48.
>>
>>$$
>>P(X\leq12.48)=0.04879
>>$$
>>
>>- We can then compare the value we get, 0.04879, to the significance level.
>>$0.04879 < 0.05$
>>$\text{and is within the critical region, so we have enough evidence to reject } H_0$
>

