---
title: "Advanced Geospatial Data Analysis in R: Environmental Application"
author: "Marj Tonini, Haokun Liu"
date: "2023-11-23"
site: bookdown::bookdown_site
documentclass: book
bibliography: [book.bib, packages.bib]
# url: your book url like https://bookdown.org/yihui/bookdown
cover-image: images/UNIL_logo.png
description: |
  This book will be used for the UNIL Master courses, and also open for the publich who are interested in. 
biblio-style: apalike
csl: chicago-fullnote-bibliography.csl
editor_options: 
  markdown: 
    wrap: sentence
---

# Preface {.unnumbered}

Earth surface environmental processes exhibit distinctive characteristics, encompassing both spatial and temporal dimensions, along with various attributes and predictive variables. Furthermore, in the era of Data Science, the wealth of available data and the rapid development of analytical models have emerged as distinctive aspects in the realm of Geospatial Data Analysis. This discipline encompasses data exploration, manipulation, and modelling, from the acquisition phase up to the visualization and interpretation of the results. Mapping where events are located and how they relate to each other provides a better understanding of the process being studied. Finally, as an increasing volume of geo-environmental data becomes more and more accessible, the demand for experts in this field is growing rapidly, both in public research institutions and in private companies. 

This eBook seeks to provide the audience with: i) a good understanding of main practical concepts and applied aspects of advanced geospatial data analysis; ii) advanced tools designed to proficiently navigate various techniques for analysing spatial datasets in geosciences.
In particular, the proposed methodological approaches will enable the audience to master a range of algorithms designed for the analysis of complex geo-environmental datasets, allowing to extract useful information and to transfom them into decisions. These include: exploratory data analyses and visualization of geographical variations in the statistical data distribution (Geographically Weighted Summary Statistics); cluster detection and mapping (e.g. Ripley’s K-function, Kernel Density Estimator, DBSCAN); Self-Organizing Maps - as an example of unsupervised machine learning approach to data clustering and visualization; Random Forest - as an example of a supervised machine learning algorithm, applied here for classification.

## Acknowledgements {.unnumbered}

We would like to thank for all the software developers who make geospatial data analysis in R possible.
Edzer Pebesma (who created the **sf** package), Robert Hijmans (who created **terra**) and Roger Bivand (who laid the foundations for much R-spatial software) have made high performance geographic computing possible in R.
