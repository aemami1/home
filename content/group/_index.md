---
draft: false
show_date: false
---

# Lab Members 

#### Director 
Ali Emami, Assistant Professor of Computer Science

#### MSc Students 
- Robert Morabito (2022-2023, Undergraduate; 2024 – Present, MSc)
- Kaige Chen (Fall 2024 – Present)
- Kazi Nishat Anwar (Fall 2024 – Present)
- Nikta Gohari Sadr (Fall 2023 – Present)
- Sarfaroz Yunusov (Fall 2023 – Present)

#### Undergraduate Researchers
- Tyler Mcdonald (Summer 2023 – Present, *NSERC Undergraduate Student Research Awardee*)
- Sangmitra Madhusudan (Summer 2024 - Present, *Brock Co-op Program*)
- Skye Reid (Summer 2024)
- QiQi Gao (Summer 2022 – Summer 2023)

#### Summer Researchers (Mitacs Globalink Interns)
- Ghofrane Faidi (Summer 2024)
- Angel Loredo (Summer 2024)
- Harsh Lalai (Summer 2024)

#### Alumni
- Abhishek Kumar, M.Sc. (Full Stack Data Systems Specialist at [360 Energy Inc.](https://www.360energy.net), 2024 – Present)

{{< figure src="/uploads/group.jpg" caption="June, 2024, Niagara Falls, Canada" >}}

{{< figure src="/uploads/acl_pic.jpg" caption="August, 2024, ACL 2024, Bangkok" >}}

# Our Mission

The Brock NLP lab is is working on developing **fair, robust, and reliable** AI systems. Our research focuses on three key areas:

1. Bias Detection and Mitigation in AI Models
2. Reasoning and Benchmarking of AI Systems
3. AI Interpretability and Reliability

# Research Areas

## 1. Bias Detection and Mitigation in AI Models

We're working on identifying and mitigating several forms of biases in AI models. We're finding recently that the very recognition and classification of what is "toxic" or "biased" is quite tricky and culturally/temporally-bound. It is now time more than ever to collaborate with experts from beyond the field (e.g., Psychology, Anthropology, Philosophy) to tackle these problems!

{{< figure src="/uploads/stoppicmorabito.png" caption="A glimpse at our latest dataset, that pits language models against increasingly and more explicitly problematic content. We find that LLMs and humans tend to disagree with what is acceptable and what is not! [Read more about this study](/publication/morabito2024stopbenchmarkinglargelanguage/).">}}

{{< figure src="/uploads/subtle.png" caption="Our work on *subtle bias* reveals a glaring extent of in popular LLMs like GPT-4 -- above is the  Proportion of GPT-4's preferred responses for the short poem task in our task suit, **CoGS**, with highlighted sectors indicating a preference for outputs from those identities. The results are alarming! [Read more about this study](/publication/kumar-2024-subtle/).">}}

{{< figure src="/uploads/debiasing.png" caption="Framework checklist comparing the consistency of recent debiasing methods.  [Read more about this study](/publication/morabito-2023-debiasing/).">}}


**Recent Publications:**
- Morabito, R., Madhusudan, S., McDonald, T., Emami, A. (2024) STOP! Benchmarking Large Language Models with Sensitivity Testing on Offensive Progressions. In *Proceedings of EMNLP 2024* 
- Kumar, A., Yunusov, S., Emami, A. (2024). Subtle Biases Need Subtler Measures: Dual Metrics for Evaluating Representative and Affinity Bias in Large Language Models. In *Proceedings of ACL 2024*.
- Morabito, R., Kabbara, J., Emami, A. (2023). Debiasing should be Good and Bad: Measuring the Consistency of Debiasing Techniques in Language Models. In *Findings of ACL 2023*.

## 2. Reasoning and Benchmarking of AI Systems

We're looking to test, harness, and push the boundaries of reasoning capabilities of AI systems. At the same time, we believe in this artificial "intelligence" as more of a *means* than an *end*. AI applied towards diversifying storytelling education, multilingual/multicultural representation, and precise language understanding are example of some of these means!

{{< figure src="/uploads/mirrorstories.png" caption="We find that LLMs are able to create personalized stories that reflect diverse identities, and we show that readers prefer them over generalized stories (whether human-written or LLM generated). Impressively, they were even better at conveying intended morals and were more engaging to readers -- this might just revolutionize how we create inclusive literature! [Read more about this study](/publication/yunusov2024mirrorstoriesreflectingdiversitypersonalized).">}}

{{< figure src="/uploads/evograd.png" caption="Interface of EvoGrad at [https://www.evograd.com/](https://evograd.com). [Read more about this study](/publication/sun-2024-evo/)." >}}

{{< figure src="/uploads/wsc+.png" caption="We developed a powerful prompting technique we coin *Tree-of-Experts* that outperforms recent techniques in having LLMs create multi-constrained challenging Winograd Schemas instances. *Paradoxially*, we also found that LLMs struggle to solve their own problems, despite providing the exact key to solution while they were constructing the sentences! We coin this the *Generation-Evaluation Inconsistency*.  [Read more about this study](/publication/zahraei-2024-wsc/).">}}

**Recent Publications:**
- Yunusov, S., Sidat, H., Emami, A. (2024) MirrorStories: Reflecting Diversity through Personalized Narrative Generation with Large Language Models. In *Proceedings of EMNLP 2024* 
- Sun, J.H., & Emami, A. (2024). EvoGrad: A Dynamic Take on the Winograd Schema Challenge with Human Adversaries. In *Proceedings of COLING-LREC 2024*.
- Zahraei, P.S., & Emami, A. (2024). WSC+: Enhancing The Winograd Schema Challenge Using Tree-of-Experts. In *Proceedings of EACL 2024*.

## 3. AI Interpretability and Reliability

We're working on probing the inner workings of AI models (frustratingly blackbox as they are!), focusing on understanding their decision-making processes, biases, and limitations to enhance their reliability, interpretability, and overall performance.

{{< figure src="/uploads/winovis.jpg" caption="In this spirit of the Winograd Schema Challenge, ever wonder if it applies multi-modally? That is, when an image generation model, like Stable Diffusion 2.0, is generating an image with antecedents and a pronoun, which antecedent does it attend to at the pronoun word? Diffusion Attentive Attribution Maps (DAAM), a recent work, makes that analysis possible, and so we applied it on a new task we created, called *WinoVis*. The results were super interesting! [Read more about this study](/publication/park-2024-winovis/)." >}}

{{< figure src="/uploads/confidence.png" caption="If a model says it's certain, does it mean it actually is? We actually have access to *two* sources of certainty in a model, its *expressed* certainty, which it can provide when asked, say, on a scale of 1-10 how certain it is, and its *internal* certainty, which can be acessed in many recent models via log probabiities of its tokens. When normalized and systematically tested, we can learn a ton about which models are most reliable/'honest' and when! [Read more about this study](/publication/kumar-2024-confidence/).">}}


**Recent Publication:**

- Park, B., Janecek, M., Li, Y., Ezzati-Jivan, N., Emami, A. (2024). Picturing Ambiguity: A Visual Twist on the Winograd Schema Challenge. In *Proceedings of ACL 2024*.

- Kumar, A., Morabito, R., Umbet, S., Kabbara, J., Emami, A. (2024). Confidence Under the Hood: An Investigation into the Confidence-Probability Alignment in Large Language Models. In *Proceedings of ACL 2024*.

Our our work is regularly presented at conferences such as ACL, EMNLP, NAACL, EACL,  COLING-LREC, ICML, and NeurIPS.

# Research Focus Areas

A fun word cloud generated from all of our research works!

{{< figure src="/uploads/wordcloud.png" >}}

# Map of Student Origins

{{< map >}}

# Join Us

We are recruiting new graduate students for Fall, 2024

**Undergraduates:** Please don't hesitate to email me to inquire about research projects that I (or better, yet, you) may have in mind. Please also attach your transcript as well as a brief description of which areas of my research interests (e.g., natural language processing) you would like to work on and why. I highly encourage, and prefer, students that are planning on a summer internship (under the NSERC USRA or SURA program), or are planning to do an Honour's thesis. 

**Graduates:** M.Sc. (<font color="blue">Computer Science</font>) and PhD (<font color="blue">Intelligent Systems and Data Science</font>) admissions are handled centrally in our department. Please see [this](https://brocku.ca/graduate-studies/future-students/apply/) page for application instructions.