---
title: "Data Version Control - DVC"
teaching: 10 # teaching time in minutes
exercises: 2 # exercise time in minutes
---

:::::::::::::::::::::::::::::::::::::: questions 

- What is data versioning?
- Why data versioning is important for reproducibility?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Describe the benefits of data versioning
- Explain how DVC relates to other tools aiming to support reusability and reproducibility 
- Configure your development environment to use DVC
- Apply DVC to a case study related to a machine learning pipeline

::::::::::::::::::::::::::::::::::::::::::::::::

## Introduction

Data versioning consist of recording incremental changes to datasets and documenting when those changes occurred.
It provides the traceability required to support reproducible geospatial modelling.

Data versioning enables users to leverage the following benefits:

- Reproduce results by retrieving the exact dataset version used to train or evaluate a model.
- Audit decisions by tracing a prediction back to the specific data that produced it.
- Debug performance changes by comparing dataset versions across experiments.
- Meet governance and compliance requirements by keeping a documented history of data modifications.


What you need to know is that there are three sections required for a valid
Carpentries lesson:

 1. `questions` are displayed at the beginning of the episode to prime the
    learner for the content.
 2. `objectives` are the learning objectives for an episode displayed with
    the questions.
 3. `keypoints` are displayed at the end of the episode to reinforce the
    objectives.

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::: instructor

Inline instructor notes can help inform instructors of timing challenges
associated with the lessons. They appear in the "Instructor View"

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: challenge 

## Challenge 1: Configuring your environment?

You want MLflow to log all your experiments to a remote tracking server at http://my-server:5000. Which line of Python code should you add before starting your run?

1. mlflow.set_experiment("http://my-server:5000")
2. mlflow.set_tracking_uri("http://my-server:5000")
3. mlflow.connect("http://my-server:5000")
4. mlflow.server.start("http://my-server:5000")

:::::::::::::::::::::::: solution 

## Output
 
```output
[2] "This new lesson looks good"
```

:::::::::::::::::::::::::::::::::


## Challenge 2: hhow data versioning can contribute to model reusability and ?

:::::::::::::::::::::::: solution 

You can add a line with at least three colons and a `solution` tag.

:::::::::::::::::::::::::::::::::
::::::::::::::::::::::::::::::::::::::::::::::::

## Figures

You can use standard markdown for static figures with the following syntax:

`![optional caption that appears below the figure](figure url){alt='alt text for
accessibility purposes'}`

![You belong in The Carpentries!](https://raw.githubusercontent.com/carpentries/logo/master/Badge_Carpentries.svg){alt='Blue Carpentries hex person logo with no text.'}

::::::::::::::::::::::::::::::::::::: callout

Callout sections can highlight information.

They are sometimes used to emphasise particularly important points
but are also used in some lessons to present "asides": 
content that is not central to the narrative of the lesson,
e.g. by providing the answer to a commonly-asked question.

::::::::::::::::::::::::::::::::::::::::::::::::


## Math

One of our episodes contains $\LaTeX$ equations when describing how to create
dynamic reports with {knitr}, so we now use mathjax to describe this:

`$\alpha = \dfrac{1}{(1 - \beta)^2}$` becomes: $\alpha = \dfrac{1}{(1 - \beta)^2}$

Cool, right?

::::::::::::::::::::::::::::::::::::: keypoints 

- Data versioning enable reproducibility but also traceability linking 
- Use `.Rmd` files for episodes when you need to generate output
- Run `sandpaper::check_lesson()` to identify any issues with your lesson
- Run `sandpaper::build_lesson()` to preview your lesson locally

::::::::::::::::::::::::::::::::::::::::::::::::

[r-markdown]: https://rmarkdown.rstudio.com/
