---
title: Adversarial patches against face detection
date: 2019-04-22
category: foresight
lang: en
---
[arxiv](https://arxiv.org/abs/1904.08653)

[more on EAI, here on adversarial](https://github.com/matt-chv/embedded-analog-intelligence/blob/master/_posts/2018-12-09-defending-against-adversarial-ai.md)

"""
Adversarial attacks on machine learning models have seen increasing interest in the past years. 
By making only subtle changes to the input of a convolutional neural network, the output of the network can be swayed to output a completely different result. 
The first attacks did this by changing pixel values of an input image slightly to fool a classifier to output the wrong class. 
Other approaches have tried to learn "patches" that can be applied to an object to fool detectors and classifiers. 
Some of these approaches have also shown that these attacks are feasible in the real-world, i.e. by modifying an object and filming it with a video camera. However, all of these approaches target classes that contain almost no intra-class variety (e.g. stop signs). The known structure of the object is then used to generate an adversarial patch on top of it. 
In this paper, we present an approach to generate adversarial patches to targets with lots of intra-class variety, namely persons
"""
