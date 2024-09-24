---
title: 'Trace-of-Thought Prompting: Investigating Prompt-Based Knowledge Distillation Through Question Decomposition'
authors:
- Tyler McDonald
- Ali Emami
date: '2024-07-09'
publication_types:
- '1'
abstract: 'Knowledge distillation allows smaller neural networks to emulate the performance of larger, teacher models with reduced computational demands. Traditional methods for Large Language Models (LLMs) often necessitate extensive fine-tuning, which limits their accessibility. To address this, we introduce Trace-of-Thought Prompting, a novel framework designed to distill critical reasoning capabilities from high-resource teacher models (over 8 billion parameters) to low-resource student models (up to 8 billion parameters). This approach leverages problem decomposition to enhance interpretability and facilitate human-in-the-loop interventions. Empirical evaluations on the GSM8K and MATH datasets show that student models achieve accuracy gains of up to 113% on GSM8K and 20% on MATH, with significant improvements particularly notable in smaller models like Llama 2 and Zephyr. Our results suggest a promising pathway for open-source, low-resource models to eventually serve as both students and teachers, potentially reducing our reliance on high-resource, proprietary models. Our code, featuring data analytics and testing scripts, is provided here: https://github.com/traceofthought/trace-of-thought-prompting/tree/main.'
publication: '*Proceedings of the 62nd Annual Meeting of the Association for Computational
  Linguistics (Student Research Workshop)* **(ACL SRW 2024)**'
links:
- name: ACL Anthology
  url: https://aclanthology.org/2024.acl-srw.35/
- name: Code
  url: https://github.com/traceofthought/trace-of-thought-prompting/
---