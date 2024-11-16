---
layout: post
title:  "Clustering Faster and Better with Projected Data"
date:   2022-11-16 00:00:00 +00:00
image: /images/projected-kmeans.png
categories: research
author: "Alibek Zhakubayev"
authors: "<strong>Alibek Zhakubayev</strong>, Greg Hamerly"
venue: "The 6th International Conference on Information System and Data Mining (ICISDM)"
---
This paper proposes a method to speed up k-means clustering by first applying random projections to reduce data dimensionality, clustering in this reduced space, and then refining the clustering in the original high-dimensional space. This approach achieves faster convergence while maintaining clustering quality, especially for high-dimensional datasets, when compared to standard methods like Hamerly's k-means
