---
title: 'STOP! Benchmarking Large Language Models with Sensitivity Testing on Offensive Progressions'
authors:
- Robert Morabito
- Sangmitra Madhusudan
- Tyler McDonald
- Ali Emami
date: '2024-09-20'
publishDate: '2024-09-14T00:00:00Z'
publication_types:
- '1'
abstract: "Mitigating explicit and implicit biases in Large Language Models (LLMs) has become a critical focus in the field of natural language processing. However, many current methodologies evaluate scenarios in isolation, without considering the broader context or the spectrum of potential biases within each situation. To address this, we introduce the Sensitivity Testing on Offensive Progressions (STOP) dataset, which includes 450 offensive progressions containing 2,700 unique sentences of varying severity that progressively escalate from less to more explicitly offensive. Covering a broad spectrum of 9 demographics and 46 sub-demographics, STOP ensures inclusivity and comprehensive coverage. We evaluate several leading closed- and open-source models, including GPT-4, Mixtral, and Llama 3. Our findings reveal that even the best-performing models detect bias inconsistently, with success rates ranging from 19.3% to 69.8%. We also demonstrate how aligning models with human judgments on STOP can improve model answer rates on sensitive tasks such as BBQ, StereoSet, and CrowS-Pairs by up to 191%, while maintaining or even improving performance. STOP presents a novel framework for assessing the complex nature of biases in LLMs, which will enable more effective bias mitigation strategies and facilitates the creation of fairer language models."
publication: '*The 2024 Conference on Empirical Methods in Natural Language Processing **(EMNLP 2024, Oral Presentation, Social Impact Paper Award)***'
#publication_short: 'ACL 2024'
links:
- name: Arxiv
  url: https://arxiv.org/abs/2409.13843
- name: Code
  url: https://github.com/Robert-Morabito/STOP
- name: Dataset
  url: https://huggingface.co/datasets/Robert-Morabito/STOP
---

This paper has been accepted for publication at the EMNLP 2024 Main Conference, to be held in November 2024. The ACL Anthology link will be available after the conference.