# Week 11 Lesson 3 #
## Introduction to General Linear Models ##

In this lesson, you will learn about general linear models. A general linear model is a flexible approach to computing model fits to the observed data where the model errors can be non-Gaussian. As was the case with linear regression, the model terms can be non-linear, however, they can't include combinations of different terms. For example, a quadratic term is allowed, but we can't have `x1 * x2`. We will use the pymc3 library to quickly and easily compute general linear models within a Bayesian framework.

###Objectives ###

By the end of this lesson, you will be able to:

- Understand the basic concepts of general linear models.  
- Be familiar with the application of general linear models in a Bayesian framework.
- Be able to use the pymc3 library to compute general linear models.

### Time Estimate ###

Approximately 2 hours.

### Readings ####

_Course Notebook_

- Explore the course [Introduction to General Linear Models][l3nb] IPython Notebook on the course JupyterHub server.

_Other Material_

- Tutorial on Bayesian Modeling in Python, [Section 4][bmps4].
- PyMC3 [Robust Regression][pymc3rr] Example
- PyMC3 [Robust Regression with Outliers][pymc3rro] Example
- Wikipedia article on [General Linear Models][wglm]

_Video_

[Week 11 Lesson 3 Video][lv]

## Optional Readings ##

- Applied AI blog on [Bayesian Inference with PyMC3][aibpymc3], Part 2.
- **[Chapter 3][bmh3]: Opening the Black Box of MCMC** from  _Bayesian Methods for Hackers_ by Cam Davidson-Pilon
- **[Chapter 4][bmh4]: The Greatest Theorem Never Told** from  _Bayesian Methods for Hackers_ by Cam Davidson-Pilon
- **[Chapter 5][bmh5]: Would you rather lose an arm or a leg?** from  _Bayesian Methods for Hackers_ by Cam Davidson-Pilon
- **[Chapter 6][bmh6]: Getting our priorities straight** from  _Bayesian Methods for Hackers_ by Cam Davidson-Pilon

### Assessment ###

When you have completed and worked through the above readings, please take the [Week 11 Lesson 3 Assessment][la]

[l3nb]: ../notebooks/intro2pp-glm.ipynb

[la]: https://learn.illinois.edu/mod/quiz/view.php?id=1844466
[lv]: https://mediaspace.illinois.edu/media/W11l3/1_1yy9vxof

[wglm]: https://en.wikipedia.org/wiki/Generalized_linear_model

[pymc3rr]: https://pymc-devs.github.io/pymc3/notebooks/GLM-robust.html
[pymc3rro]: https://pymc-devs.github.io/pymc3/notebooks/GLM-robust-with-outlier-detection.html

[bmh3]: https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/blob/master/Chapter3_MCMC/Ch3_IntroMCMC_PyMC3.ipynb

[bmh4]: https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/blob/master/Chapter4_TheGreatestTheoremNeverTold/Ch4_LawOfLargeNumbers_PyMC3.ipynb

[bmh5]: https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/blob/master/Chapter5_LossFunctions/Ch5_LossFunctions_PyMC3.ipynb

[bmh6]: https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/blob/master/Chapter6_Priorities/Ch6_Priors_PyMC3.ipynb

[bmps4]: http://nbviewer.jupyter.org/github/markdregan/Bayesian-Modelling-in-Python/blob/master/Section%204.%20Bayesian%20regression.ipynb

[aibpymc3]: http://blog.applied.ai/bayesian-inference-with-pymc3-part-2/
