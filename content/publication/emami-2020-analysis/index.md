---
title: An analysis of dataset overlap on winograd-style tasks
authors:
- Ali Emami
- Adam Trischler
- Kaheer Suleman
- Jackie Chi Kit Cheung
date: '2020-01-01'
publishDate: '2024-06-28T23:12:02.207272Z'
publication_types:
- '1'
abstract: 'The Winograd Schema Challenge (WSC) and variants inspired by it have become important benchmarks for common-sense reasoning (CSR). Model performance on the WSC has quickly progressed from chance-level to near-human using neural language models trained on massive corpora. In this paper, we analyze the effects of varying degrees of overlaps that occur between these corpora and the test instances in WSC-style tasks. We find that a large number of test instances overlap considerably with the pretraining corpora on which state-of-the-art models are trained, and that a significant drop in classification accuracy occurs when models are evaluated on instances with minimal overlap. Based on these results, we provide the WSC-Web dataset, consisting of over 60k pronoun disambiguation problems scraped from web data, being both the largest corpus to date, and having a significantly lower proportion of overlaps with current pretraining corpora.'
publication: '*COLING 2020*'
links:
- name: ACL Anthology
  url: https://aclanthology.org/2020.coling-main.515/
- name: ArXiv
  url: https://arxiv.org/abs/2011.04767
- name: Code
  url: https://github.com/aemami1/KnowRef60k
---
