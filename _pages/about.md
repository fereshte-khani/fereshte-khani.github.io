---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Senior Applied Scientist in the Office of Applied Research at Microsoft. I'm working on fair, robust, and reliable machine learning. Before joining Microsoft, I got my Ph.D. at Stanford under supervision of [Percy Liang](https://cs.stanford.edu/~pliang/) and my M.S. at MIT under supervision of [Martin Rinard](https://people.csail.mit.edu/rinard/).

**Fairness.** ML Models can lead to discrimination, and in light of their increasing prevalence, it is necessary to address this problem (see this [note](https://fereshte-khani.github.io/dml.html "note")). In my research I try to understand how we can investigate and mitigate discrimination of ML models, and how to study the feedback loops created by ML models. Previously I have shown unexpected reasons that cause ML models to exhibit discrimination. For example, adding the same amount of feature noise to all individuals ([ICML2020](https://arxiv.org/pdf/1911.09876.pdf "ICML2020"), [blog post](https://ai.stanford.edu/blog/Bluepeoplevs.Neycity/ "blog post")), or the inductive bias in overparameterized regimes ([FAccT2021](https://arxiv.org/pdf/2012.04104v1.pdf "FAccT2021"), [blog post](https://ai.stanford.edu/blog/removing-spuriousfeature/ "blog post")) can lead to discrimination. In addition, in scenarios when protected groups are not known a priori, or there is an exponential number of such groups, I showed that what kind of statistical measure is possible to measure loss discrepancy among groups ([SafeML,ICLR2019](https://arxiv.org/pdf/1906.03518.pdf)).

**Robustness.** One main concern about utilizing ML models in the real world is their poor performance in new domains, even when the new domain is slightly different from the training domain. The prevalence of unlabeled data can help ML models to perform better in new domains. I have shown how to leverage unlabeled data through pretraining and finetuning to achieve better performance in a new domain ([ICLR2021](https://arxiv.org/pdf/2012.04550v3.pdf "ICLR2021")). Furthermore, I have demonstrated how unlabeled data can be utilized to make a model robust against spurious features without losing accuracy ([FAccT2021](https://arxiv.org/pdf/2012.04104v1.pdf "FAccT2021")).

**Reliability.** When the system is learned from data, uncertainty pervades! How can we manage this uncertainty properly to achieve the precision requirement for critical applications? I am interested in selective classification where a model can abstain if it cannot provide a true prediction with high probability. Previously, I proposed a model for semantic mappings that only makes predictions if all models consistent with training data unanimously agree, resulting in 100% precision ([ACL2016](https://arxiv.org/pdf/1606.06368.pdf "ACL2016")).