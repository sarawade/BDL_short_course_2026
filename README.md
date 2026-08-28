# Bayesian Deep Learning: Short Course at ISBA 2026
Material for the short course on Bayesian Deep Learning at the [ISBA World Meeting 2026](https://isba2026.github.io), held in Nagoya, Japan, June 28 - July 3, 2026. Partly based on the Bayesian deep learning textbook [[1]](#ref-1).

The course is intended for statisticians with a background in Bayesian methods but limited exposure to deep learning, as well as machine learning practitioners familiar with neural networks who wish to better 
understand Bayesian principles. 
The course provides an introduction to Bayesian neural networks and, more broadly, to Bayesian deep learning. We begin by motivating the Bayesian approach to neural networks and reviewing the main computational strategies for posterior approximation, including variational inference, Monte Carlo methods, and scalable Bayesian algorithms. We then discuss the role of prior distributions, issues of symmetry and non-identifiability, the use of marginal likelihood for model comparison and selection, and the implications of  singular learning theory for modern deep learning models. The course will then cover a range of applications, open research challenges, and available software tools for Bayesian deep learning.  
Finally, participants will learn in a Hands-on Practical Session how to build and fit Bayesian neural networks in NumPyro, and compare MAP, variational inference, and MCMC approaches. We will also explore the impact of architectural and prior choices on predictive uncertainty and posterior predictive distributions.

Presented by: [Julyan Arbel](https://www.julyanarbel.com), [Sara Wade](https://sarawade.owlstown.net), [Vincent Fortuin](https://fortuin.github.io).

On behalf of the [BayesAI Section](https://bayesai-isba.github.io) of ISBA.

## Outline

1. Introduction and Motivation
2. Posterior Computations
3. Priors
4. Symmetries and Identifiability
5. Singular Learning Theory
6. Marginal Likelihood
7. Applications
8. Hands-on Practical

## Slides
The [slides](https://nbviewer.org/github/sarawade/BDL_short_course_2026/blob/main/slides/BDL-short-course.pdf) are available to view or download in the ``slides`` folder.

## Videos
- [Parts 1 to 5 (Julyan)](https://youtu.be/9qRj8cBHI1w)
- [Parts 6 and 7 (Vincent)](https://youtu.be/5SC0ofJ9QdM)
- [Parts 7 and 8 (Sara)](https://youtu.be/GH0z19cBuZY)

## Hands-on Practical
Materials for the practical are contained in the ``practical`` folder. 
We use [NumPyro](https://num.pyro.ai/en/latest/index.html#). If working locally, please install the relevant libraries (e.g. `numpyro`, `jax`, `pandas`, `seaborn`, 
`matplotlib`, `numpy`, `sklearn`).

Here is a [compiled version](https://htmlpreview.github.io/?https://github.com/sarawade/BDL_short_course_2026/blob/main/practical/bnn_demo_key.html) for anyone running into installation issues (and in this case, we recommend using other tools, such as [colab](https://colab.research.google.com)).

## References
<a id="ref-1"></a>
[1] Agostinelli et al. Bayesian deep learning textbook. CRC Press (in press). [[link]](https://doi.org/10.5281/zenodo.22114549).

<a id="ref-2"></a>
[2] J. Arbel, K. Pitas, M. Vladimirova, and V. Fortuin. A primer on Bayesian neural networks: review and debates. Statistical Science, 41(2):316--353, 2026 [[link]](https://projecteuclid.org/journals/statistical-science/volume-41/issue-2/A-Primer-on-Bayesian-Neural-Networks-Review-and-Debates/10.1214/24-STS969.short).

<a id="ref-3"></a>
[3] T. Papamarkou et al. Position: Bayesian deep learning is needed in the age of large-scale AI. International Conference on Machine Learning, 2024 [[link]](https://proceedings.mlr.press/v235/papamarkou24b.html).

<a id="ref-4"></a>
[4] N. Polson and V. Sokolov. Bayes, AI and Deep Learning, 2026 [[link]](https://vsokolov.org/html/_book/).
