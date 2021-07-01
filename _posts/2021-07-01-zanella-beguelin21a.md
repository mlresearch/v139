---
title: Grey-box Extraction of Natural Language Models
abstract: Model extraction attacks attempt to replicate a target machine learning
  model by querying its inference API. State-of-the-art attacks are learning-based
  and construct replicas by supervised training on the target model’s predictions,
  but an emerging class of attacks exploit algebraic properties to obtain high-fidelity
  replicas using orders of magnitude fewer queries. So far, these algebraic attacks
  have been limited to neural networks with few hidden layers and ReLU activations.
  In this paper we present algebraic and hybrid algebraic/learning-based attacks on
  large-scale natural language models. We consider a grey-box setting, targeting models
  with a pre-trained (public) encoder followed by a single (private) classification
  layer. Our key findings are that (i) with a frozen encoder, high-fidelity extraction
  is possible with a small number of in-distribution queries, making extraction attacks
  indistinguishable from legitimate use; (ii) when the encoder is fine-tuned, a hybrid
  learning-based/algebraic attack improves over the learning-based state-of-the-art
  without requiring additional queries.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: zanella-beguelin21a
month: 0
tex_title: Grey-box Extraction of Natural Language Models
firstpage: 12278
lastpage: 12286
page: 12278-12286
order: 12278
cycles: false
bibtex_author: Zanella-Beguelin, Santiago and Tople, Shruti and Paverd, Andrew and
  K{\"o}pf, Boris
author:
- given: Santiago
  family: Zanella-Beguelin
- given: Shruti
  family: Tople
- given: Andrew
  family: Paverd
- given: Boris
  family: Köpf
date: 2021-07-01
address:
container-title: Proceedings of the 38th International Conference on Machine Learning
volume: '139'
genre: inproceedings
issued:
  date-parts:
  - 2021
  - 7
  - 1
pdf: http://proceedings.mlr.press/v139/zanella-beguelin21a/zanella-beguelin21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/zanella-beguelin21a/zanella-beguelin21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
