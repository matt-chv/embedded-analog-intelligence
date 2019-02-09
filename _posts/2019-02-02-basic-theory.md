---
title: Basic theory for NN
date: 2019-02-02
category: theory
lang: en
---

Notes from [Quanta's magazine article on General Theory of NN](https://www.quantamagazine.org/foundations-built-for-a-general-theory-of-neural-networks-20190131/)

* " In 1989, it was proved [paper](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.441.7873&rep=rep1&type=pdf) (or [wiki summary](https://en.wikipedia.org/wiki/Universal_approximation_theorem))
that a neural network has only a single computational layer, but you allow that one layer to have an unlimited number of neurons,
 with unlimited connections between them, the network will be capable of performing any task you might ask of it."

* In a [paper](https://arxiv.org/abs/1705.05502) completed last year, Rolnick and Max Tegmark of the Massachusetts Institute of Technology proved that by increasing depth and decreasing width, you can perform the same functions with exponentially fewer neurons. They showed that if the situation you’re modeling has 100 input variables, you can get the same reliability using either 2100 neurons in one layer or just 210 neurons spread over two layers. They found that there is power in taking small pieces and combining them at greater levels of abstraction instead of attempting to capture all levels of abstraction at once.

* Another [paper](https://arxiv.org/abs/1810.00393) proved that at a certain point, no amount of depth can compensate for a lack of width.