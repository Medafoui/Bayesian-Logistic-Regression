# Bayesian Logistic Regression 
 
 Goal is to study how trip status variables affect the probability of being satissfied, which is the dependent variable (satisfaction).
 
 In this case study, we analyzed the factors influencing customer satisfaction using logistic regression through three distinct **approaches**: 
- the classical frequentist approach, 
- the Bayesian approach using Markov Chain Monte Carlo (MCMC), 
- and the Bayesian approach using R2OpenBUGS. 

Our aim was to predict customer satisfaction based on the predictors: Inflight entertainment, On-board service, Ease of online booking, and Check-in service.



**Comparative Insights**

- Parameter Estimates: All three methods yielded similar point estimates for the regression coefficients, indicating consistent results across different approaches.
- Uncertainty: The Bayesian approaches (both MCMC and R2OpenBUGS) offered a more comprehensive view of uncertainty through posterior distributions and credible intervals, whereas the frequentist approach provided standard errors and confidence intervals.


**Final Conclusion**

Both the classical frequentist and Bayesian approaches (MCMC and R2OpenBUGS) confirmed that *Inflight entertainment*, *On-board service*, *Ease of online booking*, and *Check-in service* are significant predictors of customer satisfaction. The Bayesian approaches, while computationally more demanding, provided deeper insights into the parameter uncertainties and were consistent with the results obtained from the frequentist approach. 
