---
title: "Modelling and model reusability and reproduciblity in the context of a case study"
teaching: 0 # teaching time in minutes
exercises: 0 # exercise time in minutes
---

:::::::::::::::::::::::::::::::::::::: questions 

- Why is model reusability and reproducibility important? 
- How can you facilitate your model reuse and reproducibility?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Describe the main phases of data-driven geospatial modelling
- Explain the importance of geospatial model reusability and reproduciblity
- Discuss the main challenges of geospatial model reusability and reproduciblity 

::::::::::::::::::::::::::::::::::::::::::::::::

## Introduction

In this lesson, you will learn why reusability and reproducibility matter in geospatial modelling.

We begin by introducing the main phases of data-driven geospatial modelling. Then, we move on to model reusability and reproducibility.

We close by discussing the main challenges of reusability and reproducibility in geospatial modelling.



## Geospatial modelling process - general workflow

data-driven approaches, meaning that models are built with parameters learned from observations’ data and aim to simulate new data minimally different from the “ground truth” under the same set of descriptive features. Among the standards guiding the implementation of data-driven model applications in general, CRISP-

In this episode we focus on data-driven approaches which mean that models learn their parameters from observations. CRISP-DM is the most well-known standard guiding data-driven modellig. The figure below illustrate the CRISP-DM adapted to geospatial data as envisoned by [1]. 

![Modelling workflow. Adapted from [1]](modelling_workflow.png){alt='Modelling workflow'} 

1. Spatial data collection


2. Spatial data analisys


3. Model building


4. Validation


5. Model deployment


## Model reusability and reproducibility

1.2	Importance (aka, the why) of geospatial model reusability and reproducibility
•	Provide examples. For instance, update/reuse models when new data / missions become available. 
•	Geospatial Foundation models are meant to be reused for various downstream tasks – using data from various EO missions

Training machine learning models require a vast mount 
### Pre-trained models



### Foundational models

## Challenges of reusability and reproducibility in geospatial modelling


	
    Reproducibility across OS / Interoperability (awareness level)
	Metadata and model documentation
	Data standards in the geosciences
	Geospatial data and model repositories 
	Specific libraries xarray and geopandas – Community standards/preferences and compatibility with MLOps
	Open models/weights for deep learning models 
	Knowledge safety. Sensitive data. 




::: discussion
why is repro important?

::: hint
this is my hint
:::

:::

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::: instructor

Inline instructor notes can help inform instructors of timing challenges
associated with the lessons. They appear in the "Instructor View"

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: challenge 

## Challenge 1: Can you do it?

What is the output of this command?

```r
paste("This", "new", "lesson", "looks", "good")
```

:::::::::::::::::::::::: solution 

## Output
 
```output
[1] "This new lesson looks good"
```

:::::::::::::::::::::::::::::::::


## Challenge 2: how do you nest solutions within challenge blocks?

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

- Use `.md` files for episodes when you want static content
- Use `.Rmd` files for episodes when you need to generate output
- Run `sandpaper::check_lesson()` to identify any issues with your lesson
- Run `sandpaper::build_lesson()` to preview your lesson locally

::::::::::::::::::::::::::::::::::::::::::::::::

## References

[1] Koldasbayeva, D., Tregubova, P., Gasanov, M. et al. Challenges in data-driven geospatial modeling for environmental research and practice. Nat Commun 15, 10700 (2024). https://doi.org/10.1038/s41467-024-55240-8



[r-markdown]: https://rmarkdown.rstudio.com/
