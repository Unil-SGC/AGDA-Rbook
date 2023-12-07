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

Earth surface environmental processes exhibit distinctive characteristics, encompassing both spatial and temporal dimensions, along with various attributes and predictive variables. Furthermore, in the era of Data Science, the wealth of available data and the rapid development of analytical models have emerged as distinctive aspects in the realm of **Geospatial Data Analysis (GDA)**. Coupled with uncertainty and complexity issues, they make this research field highly challenging. GDA encompasses data exploration, manipulation, and modelling, from the acquisition phase up to the visualization and interpretation of the results. Mapping where events are located and how they relate to each other provides a better understanding of the process being studied. Finally, as an increasing volume of geo-environmental data becomes more and more accessible, the demand for experts in this field is growing rapidly, both in public research institutions and in private companies. 

Defined for the first time by Naur as *“The science of dealing with data”*, the term **Data Science** evolved over time around the original concept of *“…converting data into information and knowledge”* (IASC, 1977). In the disciplines like environmental and earth sciences, physical geography, humanities and social sciences, the use of Data Science procedures is emerging only recently, proving to be extremely efficient to deal with the complexity of the investigated process and the heterogeneity of the underlying data sources. This leads to a cultural shift, moving scientists away from individual working within their own research domain. Indeed, disciplinary boundaries are more and more permeable, pushing scientists to be more open to collaborate among them and with decision makers on the investigation and understanding of real-world problems. Modern earth and environmental scientists need to interact with other disciplines, apparently far from their domain. This openness is increasingly important as society struggles to respond to the implications of anthropogenic pressures on different issues, such as natural hazards and climate change, or the harmful impacts of human activities on biodiversity, water and air quality, human health.

The target audience of this eBook are master and graduate (PhD) students in earth/environmental sciences, biology and spatial ecology, physical geography, and equivalent disciplines. We aim to lead students to learn theoretical concepts and practical approaches in a way that allows them to develop problem-solving strategies. The main topic covered here deals with the application of method developed in Data Science to Earth surface environmental processes. The scientific approaches related to this emerging discipline, ranging from statistics, mathematics, geomatics and computer science, are often hard to be acquired. Without omitting the importance of assuring a rigorous mathematical and statistical formalism in the methods taught, in the present eBook we put more emphasis in the practical applications in the specific domain of Geosciences. 
The book is addressed to intermediate to advanced R users with some experience on geospatial data and a great interest in geo-computing. If you have some very basic knowledge in these fields, we encourage you to explore links provided in each chapter, addressing to further useful documentation.  

**This eBook seeks to provide the audience with**: 
- A good understanding of main practical concepts and applied aspects in GDA;
- Advanced tools designed to proficiently navigate various techniques for analysing spatial datasets in geosciences.
  
In particular, the proposed methodological approaches will enable the audience to master a range of algorithms designed for the analysis of complex geo-environmental datasets, allowing to extract useful information and to transfom them into decisions. 

These include: 
- Exploratory data analyses and visualization of geographical variations in the statistical data distribution (Geographically Weighted Summary Statistics);
- Cluster detection and mapping (namelly, Ripley’s K-function, Kernel Density Estimator, DBSCAN);
- Self-Organizing Maps - as an example of unsupervised machine learning approach to data clustering and visualization;
- Random Forest - as an example of a supervised machine learning algorithm, applied here for classification.

## Prerequisites  {.unnumbered}
- Knowledge of basic statistics: methods of descriptive statistics (measures of central tendency and dispersion); how to assess relationships between variables; concepts of correlation and regression.
- Basic knowledge in geomatics (GIS): basic operations with raster and vector datasets. 
- R programming basics and RStudio.

## Acknowledgements {.unnumbered}

We would like to thank for all the software developers who make geospatial data analysis in R possible.
Edzer Pebesma (who created the **sf** package), Robert Hijmans (who created **terra**) and Roger Bivand (who laid the foundations for much R-spatial software) have made high performance geographic computing possible in R.
