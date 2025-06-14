# Project on developing a classifier to predict customer churn

Customer churn occurs when a customer leaves a company
by not paying for a subscription. It is cheaper for a company
to keep customers than to gain new customer.

The project can be done using R or python.

## Overview of the project

Most data science projects follow a standard pattern.

* selection of the data set. There are some possible options below.
* exploratory data visualizations
* building the classifier for churn prediction. This includes tuning the hyper-parameters of the classifier. If the classes are imbalanced, then specialized
techniques need
* evaluate the classifier with metrics, such as the confusion matrix, accuracy, precision and recall.
* compare the results to the results in the literature

## Some tutorial about building classifiers

To learn about the basic idea of building tabular classifiers, please
work through the following online tutorial.

* [Intro to Machine Learning](https://www.kaggle.com/learn/intro-to-machine-learning)


## Churn datasets

* [Credit Card Churn Prediction](https://www.kaggle.com/datasets/anwarsan/credit-card-bank-churn)
* [Bank customer churn](https://www.kaggle.com/datasets/mathchi/churn-for-bank-customers)

##  Final part of the project

## Explainability

* [Interpretability versus explainability](https://docs.aws.amazon.com/whitepapers/latest/model-explainability-aws-ai-ml/interpretability-versus-explainability.html)
* [Explainable Deep Learning: A Field Guide for the Uninitiated](https://arxiv.org/abs/2004.14545)
* [An introduction to explainable AI with Shapley values](https://shap.readthedocs.io/en/latest/example_notebooks/overviews/An%20introduction%20to%20explainable%20AI%20with%20Shapley%20values.html)

## Errors on the predictions 

* Investigate the use of [Conformal prediction](https://en.wikipedia.org/wiki/Conformal_prediction) to compute the error on the classifier.
* The [mapie library](https://mapie.readthedocs.io/en/latest/) implements conformal prediction.



##  Background reading on churn

*  [ChurnFM podcast on churn](https://www.churn.fm/)
*  [Tutorial Customer Churn Prediction Using Machine Learning](https://medium.com/@allanouko17/customer-churn-prediction-using-machine-learning-ddf4cd7c9fd4)

##  Background reading on machine learning

* [The Hundred-Page Machine Learning Book](https://themlbook.com/)
* [The Elements of Statistical Learning](https://hastie.su.domains/ElemStatLearn/)


##  The class imbalance problem

The techniques to train classifiers have to be modified, if the number of examples of
different classes are different sizes.

*   [Review of Methods for Handling Class-Imbalanced in Classification Problems](https://arxiv.org/pdf/2211.05456)
*   [imbalanced-learn documentation](https://imbalanced-learn.org/stable/index.html) A python library to deal with class imbalances.
*   [Survey on deep learning with class imbalance](https://journalofbigdata.springeropen.com/articles/10.1186/s40537-019-0192-5)

## Some notes on model deployment

* [How to put machine learning models into production](https://stackoverflow.blog/2020/10/12/how-to-put-machine-learning-models-into-production/)
