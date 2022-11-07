.. MIA-Visual documentation master file, created by
   sphinx-quickstart on Tue Nov  1 17:54:54 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Projet_info page
======================================
.. toctree::
   :maxdepth: 2
   :caption: Contents:

**I.	Problem Statement**

   1. In order to understand the  reliability of the modeling, we need to understand the  complexity of the model  , but it is  difficult to interpret  the  exact
   meaning of the model from numbers alone.
   2.There is a problem that it is difficult to understand the weight update process of the machine learning process because only the final weight is known.
   3.the  problem is that  it is  not intuitive to compare  by result which   model is suitable for each piece of data, and it is difficult to figure out which
   features are important.
   
   We think the above three problems can be solved through visualization. By reflecting the scale of the variables, it is possible to perform  a reliable analysis and
   intuitively understand the process of  change of  successive values.
   Existing Open Source, Matplotlib offers a variety of visualization tools, but there are no tools for the  problem we are trying to solve. Therefore, if the function
   is implemented and provided to the corresponding library, it is expected to be useful to other developers.

**II. Mission Statement**
  The three problems raised above can be solved using the following visualization tools:
  MIA_Visual (Model Intuitive Assessment_Visualization) is an open source project. ‘Learning curve analysis visualization’ helps determine if this model is reliable.
  ‘The visualization  of  the weight-update process’  helps to intuitively determine how the  weights  are being updated gradually.  Through the ‘visualization  of
  classification model performance  evaluation indicators’, it is possible to help intuitively understand each evaluation  indicator and   to help  select the
  appropriate model.
  
**III.  Features List**

  Based on original open source, we would like to add the following features. The features are described in the order in which we are planning to develop.
  1.	Visualize the learning curve to validate model complexity
  2.	Visualize the machine learning step-by-step weight update process
  3.	Visualize classification model performance evaluation metrics and feature importance indicators
  
**IV.	Target Development Language**
   -	Python

