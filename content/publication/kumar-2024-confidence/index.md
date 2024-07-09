---
title: 'Confidence Under the Hood: An Investigation into the Confidence-Probability Alignment in Large Language Models'
authors:
- Abhishek Kumar
- Robert Morabito
- Sanzhar Umbet
- Jad Kabbara
- Ali Emami
date: '2024-06-15'
publishDate: '2024-06-15T00:00:00Z'
publication_types:
- '1'
abstract: "As the use of Large Language Models (LLMs) becomes more widespread, understanding their self-evaluation of confidence in generated responses becomes increasingly important as it is integral to the reliability of the output of these models. We introduce the concept of Confidence-Probability Alignment, that connects an LLM's internal confidence, quantified by token probabilities, to the confidence conveyed in the model's response when explicitly asked about its certainty. Using various datasets and prompting techniques that encourage model introspection, we probe the alignment between models' internal and expressed confidence. These techniques encompass using structured evaluation scales to rate confidence, including answer options when prompting, and eliciting the model's confidence level for outputs it does not recognize as its own. Notably, among the models analyzed, OpenAI's GPT-4 showed the strongest confidence-probability alignment, with an average Spearman's ρ^ of 0.42, across a wide range of tasks. Our work contributes to the ongoing efforts to facilitate risk assessment in the application of LLMs and to further our understanding of model trustworthiness."
publication: '*Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics **(ACL 2024)***'
#publication_short: 'ACL 2024'
links:
- name: Arxiv
  url: https://arxiv.org/abs/2405.16282
- name: Code
  url: https://github.com/akkeshav/confidence_probability_alignment
---

This paper has been accepted for publication at the ACL 2024 Main Conference, to be held in August 2024. The ACL Anthology link will be available after the conference.