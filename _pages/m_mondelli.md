**Speaker:** Marco Mondelli (Professor, Institute of Science and Technology, Austria)
**Date:** 03-06-2025, 2pm-3pm (BST)
**Location:** Mathematical Science Building, MB0.07, University of Warwick, Coventry, UK

# Learning in the Age of LLMs: Theoretical Insights into Knowledge Distillation and Test-Time-Training

![Marco Mondelli](/assets/img/m_mondelli.jpg){: .rounded-circle}

## Abstract

The availability of powerful models pre-trained on a vast corpus of data has spurred research on alternative training methods, and the overall goal of this talk is to give theoretical insights through the lens of high-dimensional regression.


The first part considers knowledge distillation where one uses the output of a surrogate model as labels to supervise the training of a target model and, specifically, the phenomenon of weak-to-strong generalization in which a strong student outperforms the weak teacher from which the task is learned. We provide a sharp characterization of the risk of the target model for ridgeless, high-dimensional regression, under two settings: (i) model shift, where the surrogate model is arbitrary, and (ii) distribution shift, where the surrogate model is the solution of empirical risk minimization with out-of-distribution data. As a consequence, we identify the form of the optimal surrogate model, which reveals the benefits and limitations of discarding weak features in a data-dependent fashion. This has the interpretation that weak-to-strong training, with the surrogate as the weak model, can provably outperform training with strong labels under the same data budget, but it is unable to improve the data scaling law.


The second part of the talk considers test-time training (TTT) where one explicitly updates the weights of a model to adapt to the specific test instance. We investigate a gradient-based TTT algorithm for in-context learning, where we train a transformer model on the in-context demonstrations provided in the test prompt. By focusing on linear transformers when the update rule is a single gradient step, our theory (i) delineates the role of alignment between pre-training distribution and target task, (ii) demystifies how TTT can alleviate distribution shift, and (iii) quantifies the sample complexity of TTT including how it can significantly reduce the sample size required for in-context learning.

---

### About [Marco Mondelli](http://marcomondelli.com)

Marco Mondelli received the B.S. and M.S. degree in Telecommunications Engineering from the University of Pisa, Italy, in 2010 and 2012, respectively. In 2016, he obtained his Ph.D. degree in Computer and Communication Sciences at EPFL. In 2017-2019, he was a Postdoctoral Scholar in the Department of Electrical Engineering at Stanford University. In 2018, he was also a Research Fellow with the Simons Institute for the Theory of Computing, for the program on “Foundations of Data Science”. He has been a faculty member at the Institute of Science and Technology Austria (ISTA) since 2019, first as an Assistant Professor and, since 2025, as a Professor. His research interests include data science, machine learning, high-dimensional statistics, information theory, and coding theory. He is the recipient of a number of fellowships and awards, including the Jack K. Wolf ISIT Student Paper Award in 2015, the STOC Best Paper Award in 2016, the EPFL Doctorate Award in 2018, the Simons-Berkeley Research Fellowship in 2018, the Lopez-Loreta Prize in 2019, the Information Theory Society Best Paper Award in 2021 and the ERC Starting Grant in 2024.
