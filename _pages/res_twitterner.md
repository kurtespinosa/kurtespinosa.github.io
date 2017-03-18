---
layout: page
title: Project
permalink: research/res_twitterner/
subtitle: Sample work
---

## Named entity recognition (NER) in Twitter

**Learning to recognise named entities in tweets by exploiting weakly labelled data**

Named entity recognition (NER) in social media (e.g., Twitter) is a challenging task due to the noisy nature of text. As part of our participation in the W-NUT 2016 Named Entity Recognition Shared Task, we proposed an unsupervised learning approach using deep neural networks and leverage a knowledge base (i.e., DBpedia) to bootstrap sparse entity types with weakly labelled data. To further boost the performance, we employed a more sophisticated tagging scheme and applied dropout as a regularisation technique in order to reduce overfitting. Even without hand- crafting linguistic features nor leveraging any of the W-NUT-provided gazetteers, we obtained robust performance with our approach, which ranked third amongst all shared task participants according to the official evaluation on a gold standard named entity-annotated corpus of 3,856 tweets.

Paper is accessible [here](http://www.aclweb.org/anthology/W/W16/W16-39.pdf#page=165)
Github Project [here](https://github.com/kurtespinosa/ner)