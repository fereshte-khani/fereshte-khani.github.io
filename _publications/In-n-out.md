---
title: "In-N-Out: Pre-Training and Self-Training using Auxiliary Information for Out-of-Distribution Robustness"
collection: publications
permalink: /publications/in-n-out
excerpt: #'This paper is about the number 1. The number 2 is left for future work.'
date: 2021-09-01
venue: "Sang Michael Xie, Ananya Kumar, Robbie Jones, Fereshte Khani, Tengyu Ma, Percy Liang, International Conference on Learning Representations (ICLR)"
paperurl: 'https://arxiv.org/pdf/2012.04104.pdf' #'http://academicpages.github.io/files/spuriousFeature.pdf'
---

Consider a prediction setting with few in-distribution labeled examples and many unlabeled examples both in- and out-of-distribution (OOD). The goal is to learn a model which performs well both in-distribution and OOD. In these settings, auxiliary information is often cheaply available for every input. How should we best leverage this auxiliary information for the prediction task? Empirically across three image and time-series datasets, and theoretically in a multi-task linear regression setting, we show that (i) using auxiliary information as input features improves in-distribution error but can hurt OOD error; but (ii) using auxiliary information as outputs of auxiliary pre-training tasks improves OOD error. To get the best of both worlds, we introduce In-N-Out, which first trains a model with auxiliary inputs and uses it to pseudolabel all the in-distribution inputs, then pre-trains a model on OOD auxiliary outputs and fine-tunes this model with the pseudolabels (self-training). We show both theoretically and empirically that In-N-Out outperforms auxiliary inputs or outputs alone on both in-distribution and OOD error.

[Download paper here](https://arxiv.org/pdf/2012.04550)
