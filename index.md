[![Build Status](https://travis-ci.com/Model-R/modleR.svg?branch=travis)](https://travis-ci.com/Model-R/modleR) 

# modleR: a workflow for ecological niche models based on dismo <img src="articles/modleR.png" align="right" alt="" width="120" />

__modleR__ is a workflow based on package __dismo__ (Hijmans et al 2017), designed to automatize some of the common steps when performing ecological niche models. Given the occurrence records and a set of environmental predictors, it prepares the data by cleaning for duplicates, removing occurrences with no environmental information and applying some geographic and environmental filters. It executes crossvalidation or bootstrap procedures, then it performs ecological niche models using several algorithms, some of which are already implemented in the `dismo` package, and others come from other packages in the R environment, such as glm, Support Vector Machines and Random Forests.

