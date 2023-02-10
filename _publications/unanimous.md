---
title: "Unanimous Prediction for 100% Precision with Application to Learning Semantic Mappings"
collection: publications
permalink: /publications/unanimous
excerpt: #'This paper is about the number 1. The number 2 is left for future work.'
date: 2016-10-01
venue: 'Fereshte Khani, Martin Rinard, Percy Liang. Association for Computational Linguistics (ACL)'
paperurl: 'https://arxiv.org/pdf/2012.04104.pdf' #'http://academicpages.github.io/files/spuriousFeature.pdf'
---

Can we train a system that, on any new input, either says "don't know" or makes a prediction that is guaranteed to be correct? We answer the question in the affirmative provided our model family is well-specified. Specifically, we introduce the unanimity principle: only predict when all models consistent with the training data predict the same output. We operationalize this principle for semantic parsing, the task of mapping utterances to logical forms. We develop a simple, efficient method that reasons over the infinite set of all consistent models by only checking two of the models. We prove that our method obtains 100% precision even with a modest amount of training data from a possibly adversarial distribution. Empirically, we demonstrate the effectiveness of our approach on the standard GeoQuery dataset.


[Download paper here](https://arxiv.org/pdf/1606.06368.pdf)
