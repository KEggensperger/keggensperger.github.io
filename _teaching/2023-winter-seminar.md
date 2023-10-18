---
title: "Seminar: Automated Machine Learning and Hyperparameter Optimization"
collection: teaching
type: "Seminar"
permalink: /teaching/2023-winter-seminar
venue: "University of Tübingen"
date: 2023-08-22
location: "Tübingen"
---

Have you ever trained an ML model and wondered how to efficiently optimize its hyperparameters? Then this seminar is for you!

**TL;DR** AutoML aims to support ML users (and ML researchers) by automating parts of the ML workflow. In this seminar we will read some classic and also recent research papers in the field of AutoML with a focus on Bayesian optimization and AutoML systems for tabular data. 

| Course Title | Automated Machine Learning and Hyperparameter Optimization                                                                                                                                                                                 |
|--------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Course ID    | ML4501f                                                                                                                                                                                                                                    |
| Registration | [ILIAS](https://ovidius.uni-tuebingen.de/ilias3/goto.php?target=crs_4330955&client_id=pr02)                                                                                                                                                |
| ECTS         | 3                                                                                                                                                                                                                                          |
| Time         | Wednesdays 12 c.t - 14 (we will discuss the slot in out first meeting)                                                                                                                                                                     |
| Language     | english                                                                                                                                                                                                                                    |
| #participants | up to 20                                                                                                                                                                                                                                   |
| Location     | in-person at [Maria-von-Linden-Straße 6](https://uni-tuebingen.de/einrichtungen/personalvertretungen-beratung-beauftragte/lageplaene/karte-c-sand-aussenbereiche-innenstadt/maria-von-linden-strasse-6/); mostly lecture hall ground floor |

Why should you attend this seminar?
---
Besides practicing your scientific communication skills, you will also 
  * learn about key contributions in the field of AutoML
  * be able to discuss recent research in the field of hyperparameter optimization and AutoML systems
  * gain experience in reading, understanding and presenting research papers 

Requirements
---
We strongly recommend that you know the foundations of machine learning and deep learning. Ideally, you also have some experience in applying ML to get the most out of this seminar.

Topics
---
The seminar focuses on understanding the underlying concepts of modern AutoML methods. Since this field is ever-growing, in this semester, we will focus on only a few topics. 

Here is a *tentative* meeting schedule: 

| Date                             | Content                       |
|----------------------------------|-------------------------------|
| 18.10                            | Initial Meeting [[slides](https://keggensperger.github.io/files/2023_AutoMLSeminar_Intro.pdf)]  |
| 25.10; seminar room 3.OG         | Intro Session I               |
| 01.11                            | No meeting; holiday           |
| 08.11                            | HPO I (#1, #2)                |
| 15.11; 16-18; seminar room 4. OG | HPO I (#3, #4)                |
| 22.11                            | HPO I (#5, #6)                |
| 29.11                            | AutoML for Tabular (#7, #8)   |
| 06.12                            | AutoML for Tabular (#9, #10)  |
| 13.12                            | AutoML for Tabular (#11, #12) |
| 20.12                            | HPO II (#13, #14)             |
| 27.12-03.01                      | No meeting; holiday           |
| 10.01                            | Intro Session II              |
| 17.01                            | NAS (#15, #16)                |
| 24.01                            | NAS (#17, #18)                |
| 31.01                            | No Meeting                    |
| 07.02                            | NAS (#19, #20)                |


Paper List:

**HPO I**
1. [Practical Bayesian Optimization of Machine Learning Algorithms](https://papers.nips.cc/paper_files/paper/2012/file/05311655a15b75fab86956663e1819cd-Paper.pdf)
Jasper Snoek, Hugo Larochelle, Ryan P. Adams; NeurIPS 2012
2. [Input Warping for Bayesian Optimization of Non-Stationary Functions](http://proceedings.mlr.press/v32/snoek14.html)
Jasper Snoek, Kevin Swersky, Rich Zemel, Ryan Adams; ICML 2014
3. [HEBO: Pushing The Limits of Sample-Efficient Hyper-parameter Optimisation](https://dl.acm.org/doi/abs/10.1613/jair.1.13643)
Alexander I. Cowen-Rivers, Wenlong Lyu, Rasul Tutunov, Zhi Wang, Antoine Grosnit, Ryan Rhys Griffiths, Alexandre Max Maraval, Hao Jianye, Jun Wang, Jan Peters, Haitham Bou-Ammar; JAIR 2022
4. [Scalable Global Optimization via Local Bayesian Optimization](https://proceedings.neurips.cc/paper/2019/hash/6c990b7aca7bc7058f5e98ea909e924b-Abstract.html)
David Eriksson, Michael Pearce, Jacob Gardner, Ryan D. Turner, Matthias Poloczek; NeurIPS 2019
5. [BOHB: Robust and Efficient Hyperparameter Optimization at Scale](https://proceedings.mlr.press/v80/falkner18a.html)
Stefan Falkner, Aaron Klein, Frank Hutter; ICML 2018
6. [PriorBand: Practical Hyperparameter Optimization in the Age of Deep Learning](https://arxiv.org/abs/2306.12370)
Neeratyoy Mallik, Edward Bergman, Carl Hvarfner, Danny Stoll, Maciej Janowski, Marius Lindauer, Luigi Nardi, Frank Hutter; NeurIPS 2023

**AutoML for Tabular Data**
7. [Efficient and Robust Automated Machine Learning](https://proceedings.neurips.cc/paper_files/paper/2015/hash/11d0e6287202fced83f79975ec59a3a6-Abstract.html)
Matthias Feurer, Aaron Klein, Katharina Eggensperger, Jost Springenberg, Manuel Blum, Frank Hutter; NeurIPS 2015
8. [AutoGluon-Tabular: Robust and Accurate AutoML for Structured Data](https://arxiv.org/abs/2003.06505)
Nick Erickson, Jonas Mueller, Alexander Shirkov, Hang Zhang, Pedro Larroy, Mu Li, Alexander Smola; arXiv 2020
9. [Revisiting Deep Learning Models for Tabular Data](https://proceedings.neurips.cc/paper/2021/hash/9d86d83f925f2149e9edb0ac3b49229c-Abstract.html)
Yury Gorishniy, Ivan Rubachev, Valentin Khrulkov, Artem Babenko; NeurIPS 2021
10. [Why do tree-based models still outperform deep learning on tabular data?](https://proceedings.neurips.cc/paper_files/paper/2022/file/0378c7692da36807bdec87ab043cdadc-Supplemental-Datasets_and_Benchmarks.pdf)
Léo Grinsztajn, Edouard Oyallon, Gaël Varoquaux: NeurIPS 2022
11. [XTab: Cross-table Pretraining for Tabular Transformers](https://proceedings.mlr.press/v202/zhu23k/zhu23k.pdf)
Bingzhao Zhu, Xingjian Shi, Nick Erickson, Mu Li, George Karypis, Mahsa Shoaran; ICML 2023
12. [TabPFN: A Transformer That Solves Small Tabular Classification Problems in a Second](https://openreview.net/forum?id=cp5PvcI6w8_)
Noah Hollmann, Samuel Müller, Katharina Eggensperger, Frank Hutter; ICLR 2023

**HPO II**
13. [Towards Learning Universal Hyperparameter Optimizers with Transformers](https://proceedings.neurips.cc/paper_files/paper/2022/hash/cf6501108fced72ee5c47e2151c4e153-Abstract-Conference.html)
Yutian Chen, Xingyou Song, Chansoo Lee, Zi Wang, Richard Zhang, David Dohan, Kazuya Kawakami, Greg Kochanski, Arnaud Doucet, Marc'Aurelio Ranzato, Sagi Perel, Nando de Freitas, NeurIPS 2022
14. [PFNs4BO: In-Context Learning for Bayesian Optimization](https://proceedings.mlr.press/v202/muller23a.html)
Samuel Müller, Matthias Feurer, Noah Hollmann, Frank Hutter, ICML 2023

**NAS**
15. [DARTS: Differentiable Architecture Search](https://openreview.net/forum?id=S1eYHoC5FX)
Hanxiao Liu, Karen Simonyan, Yiming Yang; ICLR 2019
16. [Understanding and Simplifying One-Shot Architecture Search](https://proceedings.mlr.press/v80/bender18a.html)
Gabriel Bender, Pieter-Jan Kindermans, Barret Zoph, Vijay Vasudevan, Quoc Le; ICML 2018
17. [Once-for-All: Train One Network and Specialize it for Efficient Deployment](https://openreview.net/forum?id=HylxE1HKwS)
Han Cai, Chuang Gan, Tianzhe Wang, Zhekai Zhang, Song Han; ICLR 2020
18. [HAT: Hardware-Aware Transformers for Efficient Natural Language Processing](https://arxiv.org/abs/2005.14187)
Hanrui Wang, Zhanghao Wu, Zhijian Liu, Han Cai, Ligeng Zhu, Chuang Gan, Song Han; ACL 2020
19. [Neural Architecture Search without Training](http://proceedings.mlr.press/v139/mellor21a.html)
Joe Mellor, Jack Turner, Amos Storkey, Elliot J Crowley; ICML 2021
20. [Zero-Cost Proxies for Lightweight NAS](https://openreview.net/forum?id=0cmMMy8J5q)
Mohamed S Abdelfattah, Abhinav Mehrotra, Łukasz Dudziak, Nicholas Donald Lane; ICLR 2021

How the seminar will look like?
---

We will meet each week (with a few exceptions). In the first two weeks, we will start with introductory lectures on automated machine learning, empirical experimentation and how to critically review and present research papers. After that, each week, we will have presentations, followed by discussions.

Important information
---

Please register on ILIAS. The number of participants is limited and the registration opens on September 29th, noon. 

There will be a waiting list (please unregister to let other people take your place). 

Please come to the first lecture even if you are still on the waiting list. If you're enrolled and don't show up, your spot will be freed for someone on the waiting list.



 

