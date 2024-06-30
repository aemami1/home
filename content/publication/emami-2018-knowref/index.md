---
title: 'The KnowRef coreference corpus: Removing gender and number cues for difficult
  pronominal anaphora resolution'
authors:
- Ali Emami
- Paul Trichelair
- Adam Trischler
- Kaheer Suleman
- Hannes Schulz
- Jackie Chi Kit Cheung
date: '2018-01-01'
publishDate: '2024-06-28T23:12:02.189647Z'
publication_types:
- '1'
abstract: 'We introduce a new benchmark for coreference resolution and NLI, KnowRef, that targets common-sense understanding and world knowledge. Previous coreference resolution tasks can largely be solved by exploiting the number and gender of the antecedents, or have been handcrafted and do not reflect the diversity of naturally occurring text. We present a corpus of over 8,000 annotated text passages with ambiguous pronominal anaphora. These instances are both challenging and realistic. We show that various coreference systems, whether rule-based, feature-rich, or neural, perform significantly worse on the task than humans, who display high inter-annotator agreement. To explain this performance gap, we show empirically that state-of-the art models often fail to capture context, instead relying on the gender or number of candidate antecedents to make a decision. We then use problem-specific insights to propose a data-augmentation trick called antecedent switching to alleviate this tendency in models. Finally, we show that antecedent switching yields promising results on other tasks as well: we use it to achieve state-of-the-art results on the GAP coreference task.'
publication: '*Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics **(ACL 2019)***'
links:
- name: ACL Anthology
  url: https://aclanthology.org/P19-1386/
- name: ArXiv
  url: https://arxiv.org/abs/1811.01747
- name: Code
  url: https://github.com/aemami1/KnowRef
---
