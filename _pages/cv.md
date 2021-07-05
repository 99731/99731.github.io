---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Computer Science, *Zhejiang University*, 2010 - 2014
* Exchange student in *Simon Fraser University*, Canada, 2012 - 2013
* Visiting student in *Carnegie Mellon University(CMU)*, USA, 2017 -2018
* Ph.D in Computer Science, *Zhejiang University* (Honored Graduate), 2014 - 2019 

 
 
Work experience
======

* **Applied researcher 2 in Ads Team, eBay inc. 2021.09 - Now**
    1. Built a deep rank model with curated features to support Advertising in ebay.
    2. Proposed a pointwise and pairwise joint-learning framework for unbiased item ranking. Paper in review process.

* **Senior algorithm engineer in Search and Recommendation Team, Alibaba inc. 2019.07 - 2020.09**
    1. Built a rank model with knowledge graph and query understanding for product search in Taobao.  It is the largest scenario in Taobao (QPS $> 100K$), and the scale of training data is PB level. 
    2. Built a multi-view multi-task graph representation learning model for recommender systems in Taobao. The model is deployed online to serve $>300M$ users and gains 4\% improvement in Click through rate compared with baselines. (Paper accepted by KDD 2020)
 

* **Research Intern in Search and Recommendation Team, Alibaba inc. 2018.12 - 2019.05**
    1. Proposed an efficient graph neural network model named FlowGN for representation learning. FlowGN adopts a reverse propagation direction and decouples the layer structure from information diffusion. 
    2. Proposed a CTR prediction model that captures intra- and inter-relations of users’ multiple historical sessions with a self-attention + Bi-LSTM neural network structure.  (Paper accepted in IJCAI 2019)
 
  
   
Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!---  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
-->