# A-B-testing-results

The academic project is targeted to help an online e-commerce business owner decided whether to implement the new page or stick with the old page. 

Before going into A/B testing, firstly, I tried to look at conversion probaility between treatment group and control group. However, the probability result does not tell me which group has a higher probability of converting. Therefore, I conducted A/B test. 

I created a histogram that simulated 10000 values of differences of conversion probability between old page and new page. And I ploted the actual difference on the histogram which resulted in failing to reject the null hypothesis. 

I also used logistic regression to get the same result as A/B test. The p-value is still greater than 0.05, which means that adding a new page does not have significant impact on conversion rate. 
