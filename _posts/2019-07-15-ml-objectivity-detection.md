---
layout: post
title: Objectivity Detection with R
subtitle: Detection of objectivity in sports articles, based on co-training
gh-url: https://ansegura7.github.io/ML_ObjectivityDetection/
gh-repo: ansegura7/ML_ObjectivityDetection
gh-badge: [watch, star, fork, follow]
tags: [r, machine-learning, co-training, data-analytics, objectively-detection, tf-idf, sports-articles]
comments: true
---

Currently, many sports articles are published daily on the Internet, by various authors, which are often written objectively, on other occasions subjectively, which may not please the reader or change your perception of the facts.

In the present work, we perform a detection analysis of objectivity to a set of 1000 sports articles, previously labeled using the Mechanical Turk tool from Amazon. For this, we conducted 2 experiments in which the predictive ability of using trained statistical models with supervised versus trained learning with semi-supervised learning was compared. The fact of learning from the original file tagged by Amazon Mechanical Turk and one generated with the TMG+ algorithm based on TF-IDF was also evaluated.

The results obtained were very encouraging, since the SL approach generated better results for the original tagged file (precision close to 82.9%), while the SSL approach using Co-Training, generated better results for the dataset created with the own algorithm, with accuracy close to 74.4% using 50% of the data tagged for SSL.

Click [here](https://ansegura7.github.io/ML_ObjectivityDetection/) to see the project.
