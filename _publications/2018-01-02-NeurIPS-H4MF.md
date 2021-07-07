---
title: "Modeling dynamic missingness of implicit feedback for recommendation"
collection: publications
permalink: /publication/H4MF
excerpt: "To model and exploit the dynamics of missingness, we propose a latent variable named “user intent” to govern the temporal changes of item missingness, and a hidden Markov model to represent such a process"
date: 2018-01-02
venue: 'NeurIPS'
paperurl: "https://papers.nips.cc/paper/2018/file/8d9766a69b764fefc12f56739424d136-Paper.pdf"
citation: "https://dblp.org/rec/conf/nips/WangGZZ18.html?view=bibtex"
---
Implicit feedback is widely used in collaborative filtering methods for recommendation. It is well known that implicit feedback contains a large number of values that are missing not at random (MNAR); and the missing data is a mixture of negative and unknown feedback, making it difficult to learn users’ negative preferences. Recent studies modeled exposure, a latent missingness variable which indicates whether an item is exposed to a user, to give each missing entry a confidence of being negative feedback. However, these studies use static models and ignore the information in temporal dependencies among items, which seems to be an essential underlying factor to subsequent missingness. To model and exploit the dynamics of missingness, we propose a latent variable named “user intent” to govern the temporal changes of item missingness, and a hidden Markov model to represent such a process.

[Paper](https://papers.nips.cc/paper/2018/file/8d9766a69b764fefc12f56739424d136-Paper.pdf)
[Bibtex](https://dblp.org/rec/conf/nips/WangGZZ18.html?view=bibtex)  