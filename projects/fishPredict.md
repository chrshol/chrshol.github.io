---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "Predicting the weight of fish in catch operations"
date: 2024
published: true
labels:
  - Machine Learning
  - Python
  - Supervised learning
  - Unsupervised learning
summary: "My team developed multiple machine learning models to predict the weight of fish in a single catch operation for our INFO284 Machine Learning course at the University of Bergen."
---


For this project I worked in a team of four. Given a tabular data set that contained information about every fishery operations in Norwegian waters, our goal was to predict the fish weight for a single catch operation. To do this we trained multiple different machine learning models, and tested which one was best. 

For this project we had to start with a lot of preprocessing. The purpose of this part was to fully understand the date we were working with, visualize it and prepare it for the machine learning algorithms. After preparing the data we trained multiple different supervised models such as inear regression, random rorest regression and multilayer preception (MPL). 

Here is the results of our best supervised machine learning models:

<p align="left">
  <img src="../img/fish.png" width="600">
</p>

After this part we also used unsupervised learning by K-means clustering, which was my main responsibility for this project. K-means clustering is learning patterns and structures from input features without any explicit supervision. The goal of this part was to visualize clusters in our original high-dimensional data as well as after using PCA for dimensionality reduction.


