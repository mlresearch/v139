---
title: 'Not All Memories are Created Equal: Learning to Forget by Expiring'
abstract: Attention mechanisms have shown promising results in sequence modeling tasks
  that require long-term memory. Recent work investigated mechanisms to reduce the
  computational cost of preserving and storing memories. However, not all content
  in the past is equally important to remember. We propose Expire-Span, a method that
  learns to retain the most important information and expire the irrelevant information.
  This forgetting of memories enables Transformers to scale to attend over tens of
  thousands of previous timesteps efficiently, as not all states from previous timesteps
  are preserved. We demonstrate that Expire-Span can help models identify and retain
  critical information and show it can achieve strong performance on reinforcement
  learning tasks specifically designed to challenge this functionality. Next, we show
  that Expire-Span can scale to memories that are tens of thousands in size, setting
  a new state of the art on incredibly long context tasks such as character-level
  language modeling and a frame-by-frame moving objects task. Finally, we analyze
  the efficiency of Expire-Span compared to existing approaches and demonstrate that
  it trains faster and uses less memory.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: sukhbaatar21a
month: 0
tex_title: 'Not All Memories are Created Equal: Learning to Forget by Expiring'
firstpage: 9902
lastpage: 9912
page: 9902-9912
order: 9902
cycles: false
bibtex_author: Sukhbaatar, Sainbayar and Ju, Da and Poff, Spencer and Roller, Stephen
  and Szlam, Arthur and Weston, Jason and Fan, Angela
author:
- given: Sainbayar
  family: Sukhbaatar
- given: Da
  family: Ju
- given: Spencer
  family: Poff
- given: Stephen
  family: Roller
- given: Arthur
  family: Szlam
- given: Jason
  family: Weston
- given: Angela
  family: Fan
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
pdf: http://proceedings.mlr.press/v139/sukhbaatar21a/sukhbaatar21a.pdf
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v139/sukhbaatar21a/sukhbaatar21a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
