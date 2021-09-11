# Bayesian-Varying-Effects-Models-in-R-and-Stan

The details of the codeset and plots are included in the attached Adobe Acrobat reader (.pdf) file in this repository. 
You need to download the same to view the contents. There are referrals to other contents in BLUE colour also to follow.

In psychology, we increasingly encounter data that is nested. It is to the point now where any quantitative psychologist worth their salt must know how to analyze multilevel data. A common approach to multilevel modeling is the varying effects approach, where the relation between a predictor and an outcome variable is modeled both within clusters of data (e.g., observations within people, or children within schools) and across the sample as a whole. And there is no better way to analyze this kind of data than with Bayesian statistics. Not only does Bayesian statistics give solutions that are directly interpretable in the language of probability, but Bayesian models can be infinitely more complex than Frequentist ones. This is crucial when dealing with multilevel models, which get complex quickly.

A preview of what’s to come:

Stan is the lingua franca for programming Bayesian models. You code your model using the Stan language and then run the model using a data science language like R or Python. Stan is extremely powerful, but it is also intimidating even for an experienced programmer. In this post, I’ll demonstrate how to code, run, and evaluate multilevel models in Stan.

I assume a basic grasp of Bayesian logic (i.e., you understand priors, likelihoods, and posteriors). 

You’ll need to install the rstan package to follow along. This installation is more involved than typical R packages. The instructions on Stan’s website will help you get started.

One more note before we dive in. If you’re just starting out with Bayesian statistics in R and you have some familiarity with running Frequentist models using packages like lme4, nlme, or the base lm function, you may prefer starting out with more user-friendly packages that use Stan as a backend, but hide a lot of the complicated details. 

Stan : https://mc-stan.org/
