---
title: "Deep Session Interest Network for Click-Through Rate Prediction"
collection: publications
permalink: /publication/DSIN
excerpt: "We propose a novel CTR model named Deep Session Interest Network (DSIN) that leverages user's multiple historical sessions in their behavior sequences."
date: 2019-10-01
venue: 'IJCAI'
paperurl: "https://arxiv.org/pdf/1905.06482.pdf"
citation: "https://dblp.org/rec/conf/ijcai/FengLSWSZY19.html?view=bibtex"
---
Click-Through Rate (CTR) prediction plays an important role in many industrial applications, such as online advertising and recommender systems. How to capture users' dynamic and evolving interests from their behavior sequences remains a continuous research topic in the CTR prediction. However, most existing studies overlook the intrinsic structure of the sequences: the sequences are composed of sessions, where sessions are user behaviors separated by their occurring time. We observe that user behaviors are highly homogeneous in each session, and heterogeneous cross sessions. Based on this observation, we propose a novel CTR model named Deep Session Interest Network (DSIN) that leverages users' multiple historical sessions in their behavior sequences. We first use self-attention mechanism with bias encoding to extract users' interests in each session. Then we apply Bi-LSTM to model how users' interests evolve and interact among sessions. Finally, we employ the local activation unit to adaptively learn the influences of various session interests on the target item. Experiments are conducted on both advertising and production recommender datasets and DSIN outperforms other state-of-the-art models on both datasets.

[Paper](https://arxiv.org/pdf/1905.06482.pdf)
[Bibtex](https://dblp.org/rec/conf/ijcai/FengLSWSZY19.html?view=bibtex)  