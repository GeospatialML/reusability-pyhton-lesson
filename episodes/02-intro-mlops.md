---
title: "Introduction to MLOps"
teaching: 10 # teaching time in minutes
exercises: 2 # exercise time in minutes
---

:::::::::::::::::::::::::::::::::::::: questions 

- What is MLOps?
- How do we define MLOps workflow?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Explain data versioning 
- Manage models (train and save)
- Track experiments (key terms autologging and manual)
- Identify common MLOps tools in geospatial modeling

::::::::::::::::::::::::::::::::::::::::::::::::

## MLOps 

MLOps is a set of practices, adapted from DevOps, aimed at supporting collaboration throughout the development and deployment of machine learning models.
A core part of this is experiment reproducibility - it lets teams share, compare, and verify results with confidence. 

Machine learning models reproducibility depends on data snapshots, random seeds, hardware/library version and hyperparameters not only the source code.
MLOps tools enable capturing the entire experiment context, i.e., data version, code version, parameters, environment, resulting model and metrics.
MLOps is positioned at the convergence of machine learning, software engineering, DevOps, and data engineering.

There are several MLOps principles or best practices. However, in this lesson, we will focus on the best practices that primarily contribute to model's reuse and reproducibility such as automation, 


## Data versioning

Data versioning consist of recording incremental changes to datasets and documenting when those changes occurred.
It provides the traceability required to support reproducible geospatial modelling.

##

Let’s have a look at the directory of phenology dataset, which of the following are correct:

The link to the data is …
The version of data is ….
Data is preprocessed
Metadata is available.

## 

::::::::::::::::::::::::::::::::::::: challenge



:::::::::::::::::::::::: solution 

## Solution

The link to the data is …
The version of data is ….
Data is Not preprocessed
Metadata is available.

:::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::::


::::::::::::::::::::::::::::::::::::: keypoints 

- MLOps is a set of practices, adapted from DevOps, aimed at supporting collaboration throughout the development and deployment of machine learning models

- DevOps is a set of practices, tools and principles that combines software development (Dev) and IT operations (Ops). Automation and collaboration DevOps practices such as Continuous Integration and Continuous Delivery (CI/CD) accelerate software development, improve deployment frequency and enhance system reliability. 

::::::::::::::::::::::::::::::::::::::::::::::::

