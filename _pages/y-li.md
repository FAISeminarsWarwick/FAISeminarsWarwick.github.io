# Variational Uncertainty Decomposition for In-Context Learning

**Speaker:** Yingzhen Li (Senior Lecturer, Imperial College, UK)
**Date:** 27-05-2025, 2pm-3pm (BST)
**Location:** Mathematical Scineces Building, MB0.08, University of Warwick, Coventry, UK

![Yingzhen Li](/assets/img/y_li.jpg){: .img-fluid .rounded-circle .align-left}

## Abstract

As large language models (LLMs) gain popularity in conducting prediction tasks in-context, understanding the sources of uncertainty in in-context learning becomes essential to ensuring reliability. The recent hypothesis of in-context learning performing predictive Bayesian inference opens the avenue for Bayesian uncertainty estimation, particularly for decomposing uncertainty into epistemic uncertainty due to lack of in-context data and aleatoric uncertainty inherent in the in-context prediction task. However, the decomposition idea remains under-explored due to the intractability of the latent parameter posterior from the underlying Bayesian model. In this work, we introduce a variational uncertainty decomposition framework for in-context learning without explicitly sampling from the latent parameter posterior, by optimising auxiliary inputs as probes to obtain an upper bound to the aleatoric uncertainty of an LLM's in-context learning procedure. Through experiments on synthetic and real-world tasks, we show quantitatively and qualitatively that the decomposed uncertainties obtained from our method exhibit desirable properties of epistemic and aleatoric

---

### About [Yingzhen Li](http://yingzhenli.net/home/en/)

Dr. Yingzhen Li is currently a Senior Lecturer in machine learning at the Department of Computing at Imperial College London. She is passionate about building reliable machine learning systems that can generalise to unseen environment, and her approach combines both Bayesian statistics and deep learning.
Her research interests are two-fold and I use probabilistic ML methods to develop them: 1. Trustworthy ML models: uncertainty quantification, robustness, explainable ML, decision-making, adaptive methods (e.g., continual learning, model editing), etc. 2. Generative modelling: sequential generative models on both sequence and static data (e.g., video, spatiotemporal data, general time-series, images, tabular data, etc.), and causal representation learning with generative models. She has worked (and continue to work) extensively on approximate inference with applications to Bayesian deep learning and deep generative models. Her work on this subject has been applied in industrial systems and implemented in deep learning frameworks (e.g. Tensorflow Probability and Pyro).  Before joining Imperial, she was a senior researcher at Microsoft Research Cambridge, and previously she has interned at Disney Research. She received her PhD in engineering from the University of Cambridge, UK.
