---
title: An application of pseudo-log-likelihoods to natural language scoring
authors:
- Darren Abramson
- Ali Emami
date: '2022-01-01'
publishDate: '2024-06-28T23:12:02.219177Z'
publication_types:
- '3'
abstract: "Language models built using semi-supervised machine learning on large corpora of natural language have very quickly enveloped the fields of natural language generation and understanding. In this paper we apply a zero-shot approach independently developed by a number of researchers now gaining recognition as a significant alternative to fine-tuning for evaluation on common sense tasks. A language model with relatively few parameters and training steps compared to a more recent language model (T5) can outperform it on a recent large data set (TimeDial), while displaying robustness in its performance across a similar class of language tasks. Surprisingly, this result is achieved by using a hyperparameter-free zero-shot method with the smaller model, compared to fine-tuning to the larger model. We argue that robustness of the smaller model ought to be understood in terms of compositionality, in a sense that we draw from recent literature on a class of similar models. We identify a practical cost for our method and model: high GPU-time for natural language evaluation. The zero-shot measurement technique that produces remarkable stability, both for ALBERT and other BERT variants, is an application of pseudo-log-likelihoods to masked language models for the relative measurement of probability for substitution alternatives in forced choice language tasks such as the Winograd Schema Challenge, Winogrande, and others. One contribution of this paper is to bring together a number of similar, but independent strands of research. We produce some absolute state-of-the-art results for common sense reasoning in binary choice tasks, performing better than any published result in the literature, including fine-tuned efforts. We show a remarkable consistency of the model's performance under adversarial settings, which we argue is best explained by the model's compositionality of representations."
publication: '*arXiv preprint arXiv:2201.09377*'
links:
- name: ArXiv
  url: https://arxiv.org/abs/2201.09377
---
