# LDA-Topic-Modeling

<hr>

<br>

## Overview

This repository contains code to run a LDA (Latent Dirichlet Allocation) topic modeling. This model usually reuquires loads of memory and could be quite slow in Python. For this reason its is better to know a cuple of ways to run it quicker when datasets are outsize, in this case using Apache Spark with the Python API.

It has been done using Dataproc at Google Cloud using a cluster configuration which allows work with Jupyter Notebooks.

It has been used a dataset from Kaggle which contains over a million news headlines.

## Prerequisites

- A Google Cloud Account

- Python 3

- Pyspark v.2.2.1

- GENSIM Mallet Module

## Resources

- https://es.wikipedia.org/wiki/Latent_Dirichlet_Allocation

- https://www.kaggle.com/therohk/million-headlines

- https://radimrehurek.com/gensim/

- https://www.machinelearningplus.com/nlp/topic-modeling-gensim-python/

- https://cloud.google.com/dataproc/

- https://github.com/matthiasradtke/topic-modeling-codecentric-blog/blob/master/topicModeling-ccBlog.ipynb

- https://www.analyticsvidhya.com/blog/2016/08/beginners-guide-to-topic-modeling-in-python/

- https://medium.com/@connectwithghosh/topic-modelling-with-latent-dirichlet-allocation-lda-in-pyspark-2cb3ebd5678e

- http://spark.apache.org/docs/2.2.0/api/python/pyspark.ml.html#pyspark.ml.clustering.LDA

- https://spark.apache.org/docs/2.1.0/ml-clustering.html#latent-dirichlet-allocation-lda

- https://en.wikipedia.org/wiki/Gensim

## Python LDA Model

This notebook is based on GENSIM toolkit. 

## pySpark LDA Model

There are 2 notebooks to make it quite different ways
