---
title: The workshop
menu: main
weight: -250
---

This training workshop will focus on two statistical methods for analysing dynamic data: *Generalised Additive Mixed Modelling* (GAMM) and *Functional Data Analysis* (FDA). These techniques provide more comprehensive ways of data modelling in comparison to some traditional methods, e.g. linear regression. This is a very welcome development for experimental linguists and psychologists, who typically work with non-linear signals, such as the output of acoustic analysis, tongue movement trajectories, electroencephalography data, or eye movement trajectories. Similarly, nonlinearity is present in spatial analysis (e.g. in dialectometry), or in longitudinal analysis of sound change.

### Generalised Additive Mixed Modelling

GAMMs are an extension of linear regression models, which can capture (i) *non-linearities* in the data by using so-called smooth terms and also (ii) *dependencies across data points* representing the same participant, word, etc. through the use of random intercepts, slopes and smooths. GAMMs are incredibly flexible and are suitable for a large range of different linguistic data sets. However, they are also more complex than linear mixed effects regression models, which means that they can be harder to work with. This workshop will help you get started with GAMMs by tackling some fundamental concepts and also giving you some practice in fitting GAMMs to linguistic data.

Márton will start with a short and non-technical introduction to the general principles of GAMMs, discussing a few fundamental notions such as basis functions, smoothing penalties and random smooths. Though these concepts are typically discussed using mathematical terminology and formalisms, we will take a different approach. The focus will be on the intuitions behind these concepts, which will be amply illustrated using simple and straightforward examples from phonetics. We will then turn to the topic of significance testing using GAMMs, which is a somewhat thorny issue and therefore deserves to be discussed in detail. The rest of the workshop will be run as a practical, and we will work through a few examples together.

### Functional Data Analysis

FDA is a versatile tool that can be used for both *exploratory analysis*, e.g. when it is not yet clear how many categories/factors will be considered, as well as for *more controlled scenarios*. Using case studies, Michele will illustrate all the steps involved in analysing a set of F0 or formant contours starting from the raw data coming from Praat. An important element of novelty is the proposed way to deal with *time normalisation*. Michele will demonstrate how to integrate contour shapes and segmental durations (e.g. syllable boundaries) in FDA by representing the latter as continuous time distortion curves. This allows one to carry out a joint shape-duration analysis all within FDA , as opposed to carrying out two separate analyses, i.e. one on time-normalised curves, another on durations.

The FDA part of the workshop spans four sessions (see outline schedule). Theory and practice sessions will be interwoven, and the practical sessions will include exercises in R.
