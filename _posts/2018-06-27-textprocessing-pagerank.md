---
layout: post
title: Text Processing & PageRank
subtitle: A practical example of the use of PageRank and TF-IDF algorithms
gh-url: https://ansegura7.github.io/TextProcessing_PageRank/
gh-repo: ansegura7/TextProcessing_PageRank
gh-badge: [watch, star, fork, follow]
tags: [text-processing, pagerank, tf-idf, mrr, java]
comments: true
---

The goal of this project is to use PageRank to derive a ranking of words in a document based on their PageRank scores. The PageRank score of a word serves as an indicator of the importance of the word in the text. Also compare the MRR of the above PageRank algorithm with the MRR of a ranking of words based on their TF-IDF ranking scheme.

The project name is: HW2_PageRank and it was created using the Eclipse IDE. The program solves all the questions in a single execution (run).

For point 1, a directed graph was used (using a hash table and adjacency lists as data structures). For point 2 and 2', a function was created that returns the PageRank scores per word by document. For point 3, a parameterized function was created that generates both unigrams and n-grams. For point 4, a function was created that calculates the MRR from a list of proposed n-grams and the phrases available in the gold-standard files. For point 5, a function was created that calculates the TF-IDF scores for each word of each abstract document and then calculates the MRR score to the proposed n-grams.

Click [here](https://ansegura7.github.io/TextProcessing_PageRank/) to see the project and the repository.
