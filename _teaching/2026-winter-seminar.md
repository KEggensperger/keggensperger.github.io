---
layout: archive
title: "Seminar: Mechanistic Interpretability"
collection: teaching
type: "Seminar"
permalink: /teaching/2026-winter-seminar
venue: "TU Dortmund"
date: 2026-08-11
location: "Dortmund"
---

Neural networks are increasingly integrated into real-world decisions and everyday tasks. Current frontier models are extremely powerful, but also large and complex. We can precisely describe their architecture, control their inputs, and observe their outputs. However, it remains largely unknown what happens as data moves through dozens of layers and billions of weights. This seminar discusses the question **Can we look inside a neural network and actually explain, step by step, why it gave a particular output?**

For example, an LLM might give the correct answer to math questions, but we may not know whether the process that led to this answer generalizes to other tasks. Similarly, a model might refuse a harmful request, but from the output alone, we cannot tell whether it has genuinely learned to avoid harm or just reacts to certain trigger phrases. To safely apply LLMs, we want to detect which parts in a network are responsible for certain behaviours to intervene and control its behaviour in a desired way.

Mechanistic interpretability (MI) aims to understand what mechanisms such models learn and apply to solve tasks, and to what extent these capabilities generalize. This matters both for safety-critical applications, where predictable behaviour is essential, and for guiding improvements to future models.

This seminar we go over the basic methods and tools to gain insight into a model cognition process and introduce you to a fast-growing subfield of AI, which is increasingly relevant in research and industry.

Some more material for the curious reader:
  * [Tutorial on Mechanistic Interpretability for Language Models](https://ziyu-yao-nlp-lab.github.io/ICML25-MI-Tutorial.github.io/) from ICML 2025 by Ziyu Yao, Daking Rai
  * [Open Problems in Mechanistic Interpretability](https://arxiv.org/abs/2501.16496) - a recent paper summarizing the state of research
  * [The Urgency of Interpretability](https://darioamodei.com/post/the-urgency-of-interpretability) - a blogpost by Dario Amodei
  * [Transformer Circuits Thread](https://transformer-circuits.pub/) - a blog by Anthropic
  * [Neuronpedia](https://www.neuronpedia.org/) - an interactive website to explore AI models

| Course Title  | Mechanistic Interpretability                                                        |
|---------------|-------------------------------------------------------------------------------------|
| Course ID     | INF-MSc-102                                                                         |
| Registration  | per LSF                                                                             |
| ECTS          | 4                                                                                   |
| Time          | Thursday, 10:15-11:45                                                    |
| Language      | english                                                                             |
| #participants | max 10                                                                              |
| Location      | in-person [JvF25](https://maps.app.goo.gl/pa43gwcLJApRC56J9); seminar room 3rd floor |
| organized by  | Amir Rezaei Balef, Mykhailo Koshil, Katharina Eggensperger                          |

Requirements
---
Familiarity with foundations of deep learning, including transformer architectures and in-context learning.

Topics
---

| Date           | Content                         |
|----------------|---------------------------------|
| **15.10.2026** | **Intro I**                     |
| *22.10.2026*   | *no meeting*                    |
| **29.10.2026** | **Intro II / final assignment** |
| *05.11.2026*   | *no meeting*                    |
| *12.11.2026*   | *no meeting*                    |
| **19.11.2026** | **Foundations**                 |
| *26.11.2026*   | *no meeting*                    |
| **03.12.2026** | **Methods I**                   |
| *10.12.2026*   | *no meeting*                    |
| **17.12.2026** | **Methods II**                  |
| *24.12.2026*   | *no meeting*                    |
| *31.12.2026*   | *no meeting*                    |
| *07.01.2027*   | *no meeting*                    |
| **14.01.2027** | **Debate I**                    |
| **21.01.2027** | **Debate II**                   |
| **28.01.2027** | **Poster session**              |
| *04.02.2027*   | *no meeting*                    |


### Foundations

* [A Mathematical Framework for Transformer Circuits](https://transformer-circuits.pub/2021/framework/index.html), Elhage et al., (Transformer Circuits Thread, 2021)
* [Toy Models of Superposition](https://transformer-circuits.pub/2022/toy_model/index.html), Elhage et al., (Transformer Circuits Thread, 2022)

### Methods

* [Interpretability in the Wild: a Circuit for Indirect Object Identification in GPT-2 Small](https://openreview.net/forum?id=NpsVSN6o4ul), Wang et al., (ICLR 2023)
* [Towards Monosemanticity: Decomposing Language Models With Dictionary Learning](https://transformer-circuits.pub/2023/monosemantic-features/index.html), Bricken et al., (Transformer Circuits Thread, 2023)
* [Transcoders Find Interpretable LLM Feature Circuits](https://openreview.net/forum?id=J6zHcScAo0), Dunefsky et al., (NeurIPS 2024)
* [The Remarkable Robustness of LLMs: Stages of Inference?](https://openreview.net/forum?id=Wxh5Xz7NpJ), Lad et al., (NeurIPS 2025)

### Debate

* [Emergent World Representations: Exploring a Sequence Model Trained on a Synthetic Task](https://openreview.net/forum?id=DeG07_TcZvT), Li et al., (ICLR 2023) ↔ Counterpoint: [Evaluating the World Model Implicit in a Generative Model](https://openreview.net/forum?id=aVK4JFpegy), Vafa et al., (NeurIPS 2024)
* [Locating and Editing Factual Associations in GPT](https://openreview.net/forum?id=-h6WAS6eE4), Meng et al., (NeurIPS 2022) ↔ Counterpoint: [Does Localization Inform Editing?](https://openreview.net/forum?id=EldbUlZtbd), Hase et al., (NeurIPS 2023)
* [The Geometry of Refusal in Large Language Models: Concept Cones and Representational Independence](https://openreview.net/forum?id=80IwJqlXs8), Wollschläger et al., (ICML 2025) ↔ Counterpoint: [Refusal in Language Models Is Mediated by a Single Direction](https://openreview.net/forum?id=pH3XAQME6c), Arditi et al., (NeurIPS 2024)
* [Are Sparse Autoencoders Useful? A Case Study in Sparse Probing](https://openreview.net/forum?id=rNfzT8YkgO&noteId=hA0Ptt2IOa), Kantamneni et al., (ICML 2025) ↔ Counterpoint: [Scaling Monosemanticity: Extracting Interpretable Features from Claude 3 Sonnet](https://transformer-circuits.pub/2024/scaling-monosemanticity/), Templeton et al., (Transformer Circuits Thread, 2024)


How the seminar will look like?
---

We will meet regularly throughout the semester. In the first few weeks, we will start with introductory lectures on mechanistic interpretability and how to critically review and present research papers. After that, we will have several sessions with presentations, each followed by discussions. In the end we will have one more concluding session.

Other Important information
---

**Grading/Presentations:** Grades will be based on your presentation, slides, active participation and a final report/poster. Further details will be discussed in the first session.

**Participation/Registration:** If more students sign up than there are available topics, we will open a waiting list. Please come to the first lecture even if you are still on the waiting list. If you don't attend the first session your spot will be freed up.

 

