---
layout: post
title:  "Eight months at Scalarr"
date:   2019-12-29 11:13:54 -0400
categories:  DS Job
excerpt_separator: <!--more-->
---
For 8 months I have been working as a Data Scientist / Data Analyst at [Scalarr](https://scalarr.io/). This is my first full-time job in IT and this was an awesome experience!


As a Data Scientist in a tech startup, I participated in various stages of DS&ML development process:
 * **Analysis**
   * data cleaning
   * visualization
 * **Research**
   * feature engineering
   * data preprocessing
   * models training
   * parameters tuning
   * validation and evaluation
 * **Deployment**

 More details described here.

 <!--more-->

## Research
Our main job is to prevent fraud in advertisement market. We constantly update the models, look for new features and metrics. So far I experimented with **unsupervised learning**:
 * clusterization
 * outliers detection
 * isolation forests

**classical supervised learning**:
 * decisions trees
 * random forests
 * Gaussian Mixture Models
 * Support Vector Machines
 * Naive Bayes models
 * Gradient Boosting Machines:
   * xgboost
   * adaboost

**deep learning approaches**:
 * Feed-forward Neural Nets
 * Recurrent Neural Nets

Each experiment involved data preparation, models training, parameters tuning and evaluation.

## Models evaluation
As fraudsters invent new techniques to imitate real users (that is one example of their activities) our models should react correctly. That is somewhat similar to time series prediction validation problems.

## ETL processes
Advertisement activities generate huge amount of data - thousands of advertisement clicks every day. Arguably, plain Python does not fit for manipulating large databases.

I worked with [Dask](https://dask.org/) and [ClickHouse](https://clickhouse.yandex/) alongside with standard SQL to perform basic ETL tasks.

## Analysis optimization
Validating machine learning models often requires additional visualization that go beyond, let's say, F1-score or confusion matrix numbers. I worked on an interactive tool for Jupyter Notebook to simplify this stage.

***

Stay tuned for more!
<iframe src="https://www.linkedin.com/embed/feed/update/urn:li:share:6610880899166810112" height="600" width="504" frameborder="0" allowfullscreen="true" title="Embedded post"></iframe>
