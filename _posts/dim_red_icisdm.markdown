---
layout: post
title:  "Clustering Faster and Better with Projected Data"
image: /images/dim_red_k-means.png
categories: research
author: "Alibek Zhakubayev"
---
The K-means clustering algorithm can take a lot of time to converge, especially for large datasets
in high dimension and a large number of clusters. By applying several enhancements it is possible to
improve the performance without significantly changing the quality of the clustering. In this paper we
first find a good clustering in a reduced-dimension version of the dataset, before fine-tuning the clustering
in the original dimension. This saves time because accelerated K-means algorithms are fastest in low
dimension, and the initial low-dimensional clustering bring us close to a good solution for the original
data. We use random projection to reduce the dimension, as it is fast and maintains the cluster properties
we want to preserve. In our experiments, we see that this approach significantly reduces the time needed
for clustering a dataset and in most cases produces better results.
