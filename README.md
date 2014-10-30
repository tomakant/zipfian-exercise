zipfian-exercise
================

# Intro

This exercise will cover two seemingly disconnected topics: (1) using multi-core machines to speed up your machine learning taks, and (2) "productizing" your models as web forms or web services. 

The thread connected these two topics is our product, Domino, which makes it easy to do both of these things (and some others)

## Goals

At the end of this exercise, the following should be true:

1. Students will have several new tools in their toolbelt for making use of multi-core machines to speed up performance for their data science tasks.
2. Students will know how to use Domino to deploy models as web forms or web services
3. The Domino folks will get some valuable feedback from Zipfian students

# Prework / Setup

1. Create a Domino account (https://app.dominoup.com/signup)
2. Download the Domino client, and sign in (http://help.dominodatalab.com/client)


# Lecture

## Ways to use multiple cores for data science work

- map-reduce with mrjob
- IPython Notebook clusters
- joblib
- scikitlearn native support for parallel RandomForest, GridSearch, and cross validation

## Brief demo of Domino

- Mental model: projects, runs
- Workflow benefits: scalability, portability, tracking, sharing
- Creating web forms: Launchers
- Creating web services: API Endpoints

# Exercise

Using a data set of your choice (from your previous Zipfian exercises, or something new), use Domino to: (1) apply at least one of the multi-core techniques from the lecture to parallelize your analysis; and (2) "productize" your analysis in some way, either as a web form (using Launchers) or a web service (using API Endpoints)