---
layout: post
title: DL based Mathematica
lang: en
date: 2020-05-25
categories: [theory, deeplearning]
comments: true
---

#Deep Learning based Mathematica?

>Neural networks have a reputation for being better at solving statistical or approximate problems than at performing calculations or working with symbolic data. In
this paper, we show that they can be surprisingly good at more elaborated tasks
in mathematics, such as symbolic integration and solving differential equations
> <quote> Abstract from [arxviv](https://arxiv.org/pdf/1912.01412.pdf)</quote>

Interesting comments from reviewer
>Review: The authors use a Transformer neural network, originally architected for the purpose of language translation, to solve nontrivial mathematical equations, specifically integrals, first-order differential equations, and second-order differential equations. They also developed rigorous methods for sampling from a large space of relevant equations, which is critical for assembling the type of dataset needed for training such a data-intensive model.
Both the philosophical question posed by the paper (i.e. can neural networks designed for natural language sequence-to-sequence mappings be meaningfully applied to symbolic mathematics) and the resulting answer (i.e. yes, and such a neural network outperforms SOTA commercially-available systems) are interested in their own right, and together make a strong case for paper acceptance.
> [openreview.net](https://openreview.net/forum?id=S1eZYeHFDS)

## Question:

* Are similar research done on engineering which could be also formalised in sequential steps (Fourier transform, optimisation, ...) ?
