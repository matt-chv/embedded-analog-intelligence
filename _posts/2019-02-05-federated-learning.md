---
title: Federated Learning
date: 2019-02-05
categories: theory
lang: en
image: FederatedLearning_FinalFiles_Flow Chart1.png
---
![]({{ site.baseurl }}/static/img/FederatedLearning_FinalFiles_Flow Chart1.png)

notes from [federated learning google blog](https://ai.googleblog.com/2017/04/federated-learning-collaborative.html)
[arxiv link](https://arxiv.org/pdf/1902.01046.pdf)

Standard machine learning approaches require centralizing the training data on one machine or in a datacenter. And Google has built one of the most secure and robust cloud infrastructures for processing this data to make our services better. Now for models trained from user interaction with mobile devices, we're introducing an additional approach: Federated Learning. Federated Learning enables mobile phones to collaboratively learn a shared prediction model while keeping all the training data on device, decoupling the ability to do machine learning from the need to store the data in the cloud. This goes beyond the use of local models that make predictions on mobile devices (like the Mobile Vision API and On-Device Smart Reply) by bringing model trainingto the device as well.It works like this: your device downloads the current model, improves it by learning from data on your phone, and then summarizes the changes as a small focused update. Only this update to the model is sent to the cloud, using encrypted communication, where it is immediately averaged with other user updates to improve the shared model. All the training data remains on your device, and no individual updates are stored in the cloud. 

Notes:
[2020-03-01 update from nvidia](https://cleantechnica.com/2020/03/01/nvidia-helps-transportation-industry-with-ai-technology/)
