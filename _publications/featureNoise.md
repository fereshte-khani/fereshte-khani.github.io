---
title: "Feature Noise Induces Loss Discrepancy Across Groups"
venue: "Fereshte Khani, Percy Liang, International Conference in Machine Learning (ICML)"
collection: publications
permalink: /publications/featureNoise
excerpt: #'This paper is about the number 1. The number 2 is left for future work.'
date: 2020-10-01
paperurl: 'https://arxiv.org/pdf/2012.04104.pdf' #'http://academicpages.github.io/files/spuriousFeature.pdf'
---

The performance of standard learning procedures has been observed to differ widely across groups. Recent studies usually attribute this loss discrepancy to an information deficiency for one group (e.g., one group has less data). In this work, we point to a more subtle source of loss discrepancy---feature noise. Our main result is that even when there is no information deficiency specific to one group (e.g., both groups have infinite data), adding the same amount of feature noise to all individuals leads to loss discrepancy. For linear regression, we thoroughly characterize the effect of feature noise on loss discrepancy in terms of the amount of noise, the difference between moments of the two groups, and whether group information is used or not. We then show this loss discrepancy does not vanish immediately if a shift in distribution causes the groups to have similar moments. On three real-world datasets, we show feature noise increases the loss discrepancy if groups have different distributions, while it does not affect the loss discrepancy on datasets where groups have similar distributions.

[Download paper here](https://arxiv.org/pdf/1911.09876)
