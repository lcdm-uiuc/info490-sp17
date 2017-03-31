# Week 11 Lesson 1 #

## Introduction to Bayesian Modeling ##

In this lesson, you will about Bayesian Modeling, in which we apply Bayes rule to compute the likelihood of a model fitting a particular data set. In this approach, we encapsulate our prior knowledge of model parameters, and use the observed data to compute the likelihood of the model. By sampling from this likelihood we can compute posterior distributions for our model parameters, which allows us to fully specify the best fitting model to our data. This sampling process uses a technique known as Monte Carlo Markov Chains (MCMC). To perform Bayesian modeling, we will use the pymc3 library. 

### Objectives ###

By the end of this lesson, you will be able to:

- Understand basic concepts behind Bayesian Modeling 
- Be familiar with different prior distributions
- Be able to use the pymc3 library to perform Bayesian modeling.  

### Time Estimate ###

Approximately 2 hours.

### Readings ####

_Course Notebook_

- Explore the course [Bayesian Modeling][l1nb] IPython Notebook on the course JupyterHub server.

_Other Material_

- Applied AI blog on [Bayesian Inference with PyMC3][aibpymc3]
- Tutorial on Bayesian Modeling in Python, [Section 1][bmps1] and [Section 2][bmps2].
- Introduction to [pymc3][ipymc3]

_Video_

[Week 11 Lesson 1 Video][lv]

## Optional Readings ##

- Tutorial on [MCMC Sampling][tmcmc]
- Tutorial on Bayesian Modeling in Python, [Section 0][bmps0]
- Wikipedia article on [Probabilistic Programming Language][wppl]

- **[Chapter 1][bmh1]: Introduction to Bayesian Methods** from  _Bayesian Methods for Hackers_ by Cam Davidson-Pilon

### Assessment ###

When you have completed and worked through the above readings, please take the [Week 11 Lesson 1 Assessment][la]

[l1nb]: ../notebooks/intro2pp-bm.ipynb
[la]: https://learn.illinois.edu/mod/quiz/
[lv]: https://mediaspace.illinois.edu/media/w11l1/1_ekiiphv4

[wppl]: https://en.wikipedia.org/wiki/Probabilistic_programming_language

[aibpymc3]: http://blog.applied.ai/bayesian-inference-with-pymc3-part-1/

[tmcmc]: http://twiecki.github.io/blog/2015/11/10/mcmc-sampling/
[bmh1]: https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/blob/master/Chapter1_Introduction/Ch1_Introduction_PyMC3.ipynb

[ipymc3]: https://pymc-devs.github.io/pymc3/notebooks/getting_started.html

[bmps0]: http://nbviewer.ipython.org/github/markdregan/Bayesian-Modelling-in-Python/blob/master/Section%200.%20Introduction.ipynb
[bmps1]: http://nbviewer.jupyter.org/github/markdregan/Bayesian-Modelling-in-Python/blob/master/Section%201.%20Estimating%20model%20parameters.ipynb
[bmps2]: http://nbviewer.ipython.org/github/markdregan/Bayesian-Modelling-in-Python/blob/master/Section%202.%20Model%20checking.ipynb
