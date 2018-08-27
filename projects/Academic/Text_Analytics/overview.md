---
layout: default
title: Text Analytics Assignments - Overview
---

# Text Analytics Assignments - Overview

In general, I haven not included the dataset provided to us - as this might be part of ongoing research. However, wherever possible, I have shared the public version hosted / the specific site the data was scraped from.

## Assignment 1:

#### Part A:
Part A of this assignment mainly concentrates on some basic text mining tasks just to familiarize oneself with the nuances of putting text mining theories to practice with Python scripts. Additionally, we were asked to explore POS-tagging, Zipf's Law, stopwords & lemmatization.

#### Part B:
Part B involves building and testing classification models to predict salaries from the text contained in the job descriptions. We were tasked with using a Naive Bayes Classifier and evaluate performance with just Bag-of-words, n-grams, removing stopwords, lemmatization, and adding POS-tag.

#### Data + Code:
The data for this assignment can be found on [Kaggle](http://www.kaggle.com/c/job-salary-prediction). You can find the notebook submission here: _add link to jupyter/nbviewer here_.



## Assignment 2: 

The second assignment conentrates on the _voice of the crowd_: We reviewed data from Yelp Restaurant Reviews dataset. We implemented ideas from [this](www.aclweb.org/anthology/P02-1053.pdf) paper titled _Thumbs Up or Thumbs Down? Semantic Orientation Applied to Unsupervised Classification of Reviews_ in Task E.

#### Task A:
We built a binary classifier on non-text data. Eg: stars, votes_funny,votes_cool,votes_useful, cheap,moderate,expensive..., American,Chinese,Indian..., etc.  

#### Task B:
We built a binary classifier on text data only.

#### Task C:
Combined tasks A + B and reviewed performance.

#### Task D:
Added sentiment analysis and ran another model on text + Sentiment data. Compared results.

#### Task E:
Implemented Pointwise Mutual Information (PMI) and ran another model on text + PMI + Sentiment data. Compared results to D.

#### Task F:
We studied the top attributes of a restaurant that are associated with high/low ratings - eg: service, ambience, etc.

#### Data + Code:
The data for this assignment was text data from the Yelp Reviews dataset. Although I cannot verify if the same cleaned version that were provided is available online, one can easily relate the major elements in the EDA to what you see [here](https://www.yelp.com/dataset/). You can find the notebook submission here: _add link to jupyter/nbviewer here_.




## Assignment 3:

Here, we were tasked to implement the approach from [this](https://dl.acm.org/citation.cfm?id=2407744) paper - _Product Comparison Networks for Competitive Analysis of Online Word-of-Mouth_ on a different dataset. The paper deals with online reviews on Amazon on camera, while we studied if the same mechanism existed in car sales forums like [Edmunds](https://www.edmunds.com/car-reviews/)

#### Task A:
We were asked to build a product comparison network just using just sentiment scores and calculate the corresponding PageRanks.


#### Task B:
We created 2 flavors of the original PageRank algorithm - weighted & unweighted (same as the original). And we analyzed the additional information that weighted PageRank captures. 

#### Task C:
We build a custom sentiment analyser and recalculate weighted PageRank on the new scores - and compare this to what we saw in Task A & B.

#### Data + Code:
The data for this assignment was scraped from Edmunds.com, cleaned and tagged to ID car models. You can find the notebook submission here: _add link to jupyter/nbviewer here_.