# Hierarchical-Model-for-Sales_YOY-Prediction
## Target
Alternative data such as credit card and web data allow investors to monitor company fundamentals on a real-time basis. So, a model has good performance on forecasting a company’s actual reported sales growth is very useful and meaningful. Here, we want to use panel sales data of multiple companies to make prediction on a company’s sales growth rate on next delivery date.
## Method
> 
I create six models to achieve this target. They all belong to Hierarchical model with Bayesian Method, but different model allows different parameters to vary by group. 
> 
Hierarchical or multilevel modeling is a generalization of regression modeling. Multilevel models are regression models in which the constituent model parameters are given probability models. This implies that model parameters are allowed to vary by group, which means we can keep the independence of each company while making use of all companies’ data.  
> 
Generally speaking, a company's sales growth rate is relatively stable in a certain period of time, which means that sales growth rate has a high correlation with the company's previous performance. So, I add group-level predictors to model this characteristic.
> 
Also, our models are implemented with Bayesian Method to improve the performance of prediction.
## Implement toolbox--PYMC3
All the six models are implemented under a python package named PYMC3.
> 
Introduction: PyMC3 is a probabilistic programming module for Python that allows users to fit Bayesian models using a variety of numerical methods, most notably Markov chain Monte Carlo (MCMC) and variational inference (VI). Its flexibility and extensibility make it applicable to a large suite of problems. Along with core model specification and fitting functionality, PyMC3 includes functionality for summarizing output and for model diagnostics.

### The detail of this project please see the "documentation.pdf" file.
