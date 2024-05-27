---
title: "QDN: A Quadruplet Distributor Network for Temporal Knowledge Graph Completion."
collection: publications
permalink: /publication/2023-05-04-paper-title-number-4
excerpt: 'Temporal knowledge graph completion (TKGC) is an extension of the traditional static knowledge graph completion (SKGC) by introducing the timestamp. The existing TKGC methods generally translate the original quadruplet to the form of the triplet by integrating the timestamp into the entity/relation, and then use SKGC methods to infer the missing item. However, such an integrating operation largely limits the expressive ability of temporal information and ignores the semantic loss problem due to the fact that entities, relations, and timestamps are located in different spaces. In this article, we propose a novel TKGC method called the q uadruplet d istributor n etwork (QDN) , which independently models the embeddings of entities, relations, and timestamps in their specific spaces to fully capture the semantics and builds the QD to facilitate the information aggregation and distribution among them. Furthermore, the interaction among entities, relations, and timestamps is integrated using a novel quadruplet-specific decoder, which stretches the third-order tensor to the fourth-order to satisfy the TKGC criterion. Equally important, we design a novel temporal regularization that imposes a smoothness constraint on temporal embeddings. Experimental results show that the proposed method outperforms the existing state-of-the-art TKGC methods.'
date: 2023-05-04
#venue: 'GitHub Journal of Bugs'
paperurl: 'https://ieeexplore.ieee.org/document/10132432'
citation: 'Jiapu Wang, Boyue Wang, Junbin Gao, Xiaoyan Li, Yongli Hu, Baocai Yin. QDN: A Quadruplet Distributor Network for Temporal Knowledge Graph Completion. IEEE Transactions on Neural Networks and Learning Systems[J], 2023.'
---
