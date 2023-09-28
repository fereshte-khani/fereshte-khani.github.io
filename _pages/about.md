---
permalink: /
# title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Senior Applied Scientist in the Office of Applied Research at Microsoft. Before joining Microsoft, I got my Ph.D. at Stanford under supervision of [Percy Liang](https://cs.stanford.edu/~pliang/) and my M.S. at MIT under supervision of [Martin Rinard](https://people.csail.mit.edu/rinard/).

## <a name="research"></a>Research

**Alignment.**
Alignment is ensuring machine learning models conform to human values and intentions.
My [previous work](https://arxiv.org/pdf/2305.12219.pdf) focuses on collaborative alignment, where multiple individuals engage with the model and each other to align the model to their preference without interferring other users.
I envision a future where NLP models are developed in a collaborative fashion, similar to open source software or Wikipedia, benefiting from diverse user inputs for improved quality and fairness. 
For this scenario to materialize, we need to help users to convey knowledge, and verify the impact of their proposed changes to models, similar to “diffs” or “regression tests”. 
[CoDev](https://arxiv.org/pdf/2305.12219.pdf) is a small step in this direction.
In [TACL2018](https://arxiv.org/pdf/1805.11774.pdf), we showed how human use pragmatics, planning, and inference in dialogue to convey information. 


**Robustness.** One main concern about utilizing ML models in the real world is their poor performance in new domains, even when the new domain is slightly different from the training domain. 
In my previous work, we have shown how to leverage unlabeled data through pretraining and finetuning to achieve better performance in a new domain ([ICLR2021](https://arxiv.org/pdf/2012.04550v3.pdf "ICLR2021")); and how to use unlabeled data to make a model robust against spurious features ([FAccT2021](https://arxiv.org/pdf/2012.04104v1.pdf "FAccT2021")).
In [ACL2023](https://arxiv.org/pdf/2305.17804.pdf), we showed how to use LLMs as a large pool of unlabeled data to augment groups that the model has low performance on.

**Reliability.** How can we have a reliable model that knows when it does not know? I am interested in selective classification where a model can abstain if it cannot provide a true prediction with high probability. 
Previously, I proposed a model that only predicts if all models consistent with training data unanimously agree, resulting in 100% precision ([ACL2016](https://arxiv.org/pdf/1606.06368.pdf "ACL2016")).
However, as models become more complicated we cannot do the unanimous agreement anymore! In ([Neurips2022](https://arxiv.org/pdf/2210.00055.pdf)), we show how to find two disjoint models and only predicts if those two model agree. 


**Fairness.** ML Models can lead to discrimination, and in light of their increasing prevalence, it is necessary to address this problem (see this [post](https://fereshte-khani.github.io/dml.html)). In my research I try to understand how we can investigate and mitigate discrimination of ML models, and how to study the feedback loops created by ML models. 
Previously I have shown unexpected reasons that cause ML models to exhibit discrimination. For example, adding the same amount of feature noise to all individuals ([ICML2020](https://arxiv.org/pdf/1911.09876.pdf "ICML2020"), [blog post](https://ai.stanford.edu/blog/Bluepeoplevs.Neycity/ "blog post")), or the inductive bias in overparameterized regimes ([FAccT2021](https://arxiv.org/pdf/2012.04104v1.pdf "FAccT2021"), [blog post](https://ai.stanford.edu/blog/removing-spuriousfeature/ "blog post")) can lead to discrimination. In addition, in scenarios when protected groups are not known a priori, or there is an exponential number of such groups, I showed that what kind of statistical measure is possible to measure loss discrepancy among groups ([SafeML,ICLR2019](https://arxiv.org/pdf/1906.03518.pdf)).

## <a name="honors"></a>Honors

- Enhancing Diversity in Graduate Education (EDGE) Doctoral Fellowship, 2016-2022.
- Ranked 3rd in the Asia Regional ACM-ICPC Contest, Iran, 2010.
- Silver Medal in International Olympiad in Informatics (IOI) 2009, Plovdiv, Bulgaria.
- Selected as a national scientific elite and the recipient of the grant from the Iranian National Elites Foundation 2009 - 2013.
- Gold Medal in Iranian National Olympiad in Informatics (INOI), 2008.
- Awarded winter school grant from Chinese University of Hong Kong, Hong Kong, 2011

## <a name="teaching_services"></a>Teaching and Services

- Teaching Assistant for Machine Learning, Stanford, Summer 2020, Fall 2020 <font size='2'>[[review of linear algebra]](https://cs229.stanford.edu/livenotes2020spring/linearalgebra-slides.pdf)[[probability theory review]](https://cs229.stanford.edu/section/cs229_spring2020_prob_review_slides.pdf)</font>
- Teaching Assistant for Data Structure (2011), Artificial Intelligence (2011), and Design of Algorithm (2012), Sharif University of Technology.
- Lecturer in Summer Math Camp , Farzanegan Highschool, 2007 - 2013
- Teaching students for Iranian National Olympiad in Informatics (INOI), 2009 - 2011
- Contest Designer of Iranian National Olympiad in Informatics (first round), 2011

---

- Reviewer for NeurIPS, ICML, ICLR, ALT, ACL
- Stanford computer science admission committee, 2018

---

- Speaker and panelist in [trustML-Unlimited](https://sites.google.com/view/trustml-unlimited/home), ICLR 2023
- Panelist on Application of AI with Peter Norvig at [the nightcap](https://www.thenightcap.com/), 2023
- Co-Moderator in Women in Data Science (WiDS) Conference (NLP breakout), 2017
- Stanford CS PhD representative at Grace Hopper conference, 2017
- Member of the Scientific Committee, Computer Vision Workshop, Iran, 2012


## Other activities

In my free time, I like [reading](https://www.goodreads.com/user/show/38546723-fereshte-khani), writing, running, hiking and backpacking. 