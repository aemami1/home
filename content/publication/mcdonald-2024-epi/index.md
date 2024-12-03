---
title: 'Can We Afford The Perfect Prompt? Balancing Cost and Accuracy with the Economical Prompting Index'
authors:
- Jing Han Sun
- Ali Emami
date: '2024-11-29'
publishDate: '2024-11-29T00:00:00Z'
publication_types:
- '1'
abstract: 'As prompt engineering research rapidly evolves, evaluations beyond accuracy are crucial for developing cost-effective techniques. We present the Economical Prompting Index (EPI), a novel metric that combines accuracy scores with token consumption, adjusted by a user-specified cost concern level to reflect different resource constraints. Our study examines 6 advanced prompting techniques, including Chain-of-Thought, Self-Consistency, and Tree of Thoughts, across 10 widely-used language models and 4 diverse datasets. We demonstrate that approaches such as Self-Consistency often provide statistically insignificant gains while becoming cost-prohibitive. For example, on high-performing models like Claude 3.5 Sonnet, the EPI of simpler techniques like Chain-of-Thought (0.72) surpasses more complex methods like Self-Consistency (0.64) at slight cost concern levels. Our findings suggest a reevaluation of complex prompting strategies in resource-constrained scenarios, potentially reshaping future research priorities and improving cost-effectiveness for end-users.'
publication: '*The 31st International Conference on Computational Linguistics (COLING 2025)***'
#publication_short: 'COLING 2025'
links:
- name: ArXiv
  url: https://arxiv.org/abs/2412.01690
  name: Code
  url: https://github.com/tm21cy/EconomicalPromptingIndex
  name: ACL Anthology (TBH)
  url:
---