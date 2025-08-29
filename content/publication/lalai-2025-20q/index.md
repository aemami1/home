---
title: 'The World According to LLMs: How Geographic Origin Influences LLMs Entity Deduction Capabilities'
authors:
- Harsh Nishant Lalai, 
- Raj Sanjay Shah
- Jiaxin Pei
- Sashank Varma
- Yi-Chia Wang
- Ali Emami
date: '2025-08-01'
publishDate: '2025-08-1T23:12:02.247873Z'
publication_types:
- '1'
abstract: 'Large Language Models (LLMs) have been extensively tuned to mitigate explicit biases, yet they often exhibit subtle implicit biases rooted in their pre-training data. Rather than directly probing LLMs with human-crafted questions that may trigger guardrails, we propose studying how models behave when they proactively ask questions themselves. The 20 Questions game, a multi-turn deduction task, serves as an ideal testbed for this purpose. We systematically evaluate geographic performance disparities in entity deduction using a new dataset, Geo20Q+, consisting of both notable people and culturally significant objects (e.g., foods, landmarks, animals) from diverse regions. We test popular LLMs across two gameplay configurations (canonical 20-question and unlimited turns) and in seven languages (English, Hindi, Mandarin, Japanese, French, Spanish, and Turkish). Our results reveal geographic disparities: LLMs are substantially more successful at deducing entities from the Global North than the Global South, and the Global West than the Global East. While Wikipedia pageviews and pre-training corpus frequency correlate mildly with performance, they fail to fully explain these disparities. Notably, the language in which the game is played has minimal impact on performance gaps. These findings demonstrate the value of creative, free-form evaluation frameworks for uncovering subtle biases in LLMs that remain hidden in standard prompting setups. By analyzing how models initiate and pursue reasoning goals over multiple turns, we find geographic and cultural disparities embedded in their reasoning processes.'
publication: '*COLM 2025*'
links:
- name: Arxiv
  url: https://arxiv.org/abs/2508.05525
- name: Code + Website
  url: https://sites.google.com/view/llmbias20q/home
- name: Dataset
  url: https://github.com/Harsh-Lalai/Geo20QPlus
---
