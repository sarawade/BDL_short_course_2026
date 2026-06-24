# Bayesian Deep Learning: Short Course at ISBA 2026
Material for the short course on Bayesian Deep Learning at the [ISBA World Meeting 2026](https://isba2026.github.io), held in Nagoya, Japan, June 28 - July 3, 2026.

The course is intended for statisticians with a background in Bayesian methods but limited exposure to deep learning, as well as machine learning practitioners familiar with neural networks who wish to better 
understand Bayesian principles. 
The course provides an introduction to Bayesian neural networks and, more broadly, to Bayesian deep learning. We begin by motivating the Bayesian approach to neural networks and reviewing the main computational strategies for posterior approximation, including variational inference, Monte Carlo methods, and scalable Bayesian algorithms. We then discuss the role of prior distributions, issues of symmetry and non-identifiability, the use of marginal likelihood for model comparison and selection, and the implications of  singular learning theory for modern deep learning models. The course will then cover a range of applications, open research challenges, and available software tools for Bayesian deep learning.  
Finally, participants will learn in a Hands-on Practical Session how to build and fit Bayesian neural networks in NumPyro, and compare MAP, variational inference, and MCMC approaches. We will also explore the impact of architectural and prior choices on predictive uncertainty and posterior predictive distributions.

Presented by: [Julyan Arbel](https://www.julyanarbel.com), [Sara Wade](https://sarawade.owlstown.net), [Vincent Fortuin](https://fortuin.github.io).

On behalf of the [BayesAI Section](https://bayesai-isba.github.io) of ISBA.

## Course Outline:

1. Introduction and Motivation
2. Posterior Computations
3. Priors
4. Symmetries and Identifiability
5. Marginal Likelihood
6. Singular Learning Theory
7. Applications
8. References and Outlook
9. Hands-on Practical

There will be a Coffee break (20 min).

## Hands-on Practical
Materials for the practical are contained in the ``practical`` folder. 
We will use [NumPyro](https://num.pyro.ai/en/latest/index.html#). If working locally, please install the relevant libraries (e.g. `numpyro`, `jax`, `pandas`, `seaborn`, 
`matplotlib`, `numpy`, `sklearn`).

Here is a [compiled version](https://htmlpreview.github.io/?https://github.com/sarawade/BDL_short_course_2026/blob/main/practical/bnn_demo_key.html) for anyone running into installation issues (and in this case, we recommend using other tools, such as [colab](https://colab.research.google.com).
