# Resurrecting Recurrent Neural Networks

![Razvan Pascanu ](/assets/img/razvan-pascanu.jpg){: .img-fluid .rounded-circle .align-left width="300px"}

**Speaker:** Razvan Pascanu (Google DeepMind, UK)
**Date:** 26-11-2024, 2pm-3pm (BST)
**Location:** Computer Science building, CS1.04, University of Warwick, Coventry, UK


## Abstract

In this talk I will focus on State Space Models (SSMs) , a subclass of Recurrent Neural Networks (RNNs) that has recently gained some attention through works like Mamba, obtaining strong performance against transformer baselines. I will start by first explaining how SSMs can be viewed as just a particular parametrization of RNNs and what are the crucial differences compared to previous recurrent architectures that led to these results. My goal is to demystify the relative complex parametrization of the architecture and identify what elements are needed for the model to perform well. In this process I will introduce the Linear Recurrent Unit (LRU), a simplified linear layer inspired by existing SSM layers. In the second part of the talk, I will focus on language modelling and the block structure in which such layers tend to be embedded. I will argue that beyond the recurrent layer itself, the block structure borrowed from transformers plays a crucial role in the recent successes of this architecture, and present results at scale of well performing hybrid recurrent architectures as compared to strong transformer baseline. If time allows I will expand the discussion to video, presenting a few ways SSM can have an impact in video modeling. I will close the talk with a few open questions and thoughts on the importance of recurrence in modern deep learning models.

---

### About [Razvan Pascanu]((https://sites.google.com/view/razp/home))

Razvan Pascanu is currently a Research Scientist at DeepMind. He obtained a PhD in Computer Science from the University of Montreal (2014), supervised by Prof. Yoshua Bengio, and an MSc from Jacobs University Bremen (2009) under Prof. Herbert Jaeger. He has contributed to the development of Theano and authored deep learning tutorials for it, publishing several impactful works in deep learning and reinforcement learning. His research interests span optimization and learning, focusing on efficient and scalable optimization methods, data-efficient learning in reinforcement learning, and understanding learning dynamics. He is also deeply interested in memory mechanisms in RNNs, multi-task learning paradigms like continual learning and meta-learning, graph neural networks, and theoretical aspects of deep networks. Beyond research, he has actively contributed to the machine learning community as an organizer for EEML and AIRomania, where he has led Romanian AI Days since 2020 and developed AI courses for high school students. Additionally, he has been involved in organizing conferences such as the Lifelong Learning Conference (lifelong-ml.cc) and the Log Conference on Graph Neural Networks (logconference.org).


