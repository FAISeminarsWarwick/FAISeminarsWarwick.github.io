# Adversarial Training Should Be Cast as a Non-Zero-Sum Game

![Volkan Cevher](/assets/img/volkan_cevher.jpg){: .img-fluid .rounded-circle .align-right}

**Speaker:** Volkan Cevher  
**Date:** 2024-04-26  
**Location:** Foundation of AI | Seminars | Warwick  

## Abstract

One prominent approach toward resolving the adversarial vulnerability of deep neural networks is the two-player zero-sum paradigm of adversarial training, in which predictors are trained against adversarially-chosen perturbations of data. Despite the promise of this approach, algorithms based on this paradigm have not engendered sufficient levels of robustness and suffer from pathological behavior like robust overfitting.

To understand this shortcoming, we first show that the commonly used surrogate-based relaxation used in adversarial training algorithms voids all guarantees on the robustness of trained classifiers. The identification of this pitfall informs a novel non-zero-sum bilevel formulation of adversarial training, wherein each player optimizes a different objective function.

Our formulation naturally yields a simple algorithmic framework that matches and in some cases outperforms state-of-the-art attacks, attains comparable levels of robustness to standard adversarial training algorithms, and does not suffer from robust overfitting.

---

### About Volkan Cevher

Volkan Cevher is a renowned researcher in the field of artificial intelligence, focusing on the intersection of adversarial machine learning and robust algorithm design. His work has paved the way for new understandings and methodologies in making AI systems more secure and dependable.
