---
layout: speaker
permalink: /speakers/a-gretton
title: Arthur Gretton
position: Professor, UCL, UK
description: Foundations of AI | Seminars | Warwick
---

# Causal Effect Estimation with Context and Confounders

![Arthur Gretton](/assets/img/agretton.jpg){: .img-fluid .rounded-circle .align-left}

**Speaker:** Arthur Gretton (Gatsby, UCL)
**Date:** This talk will be rescheduled
**Location:** Zeeman Building, Mainsite, MS0.05, University of Warwick, Coventry, UK

[Download iCalendar File](/assets/ics/event.ics)

## Abstract

A fundamental causal modelling task is to predict the effect of an intervention (or treatment) on an outcome, given context/covariates. Examples include predicting the effect of a medical treatment on patient health given patient symptoms and demographic information, or predicting the effect of ticket pricing on airline sales given seasonal fluctuations in demand. The problem becomes especially challenging when the treatment and context are complex (for instance, "treatment" might be a web ad design or a radiotherapy plan), and when only observational data is available (i.e., we have access to historical data, but cannot intervene ourselves). The challenge is greater still when the covariates are not observed, and constitute a hidden source of confounding.

I will give an overview of some practical tools and methods for estimating causal effects of complex, high dimensional treatments from observational data. The approach is based on conditional feature means, which represent conditional expectations of relevant model features. These features can be deep neural nets (adaptive, finite dimensional, learned from data), or kernel features (fixed, infinite dimensional, enforcing smoothness). When hidden confounding is present, a neural net implementation of instrumental variable regression can be used to correct for this confounding. The methods will be applied to modelling employment outcomes for the US Job Corps program for Disadvantaged Youth, and in policy evaluation for reinforcement learning.

---

### About Arthur Gretton

Arthur Gretton is a Professor with the Gatsby Computational Neuroscience Unit, and director of the Centre for Computational Statistics and Machine Learning (CSML) at UCL; and a research scientist at Google Deepmind. His recent research interests include causal inference and representation learning, design and training of generative models, and nonparametric hypothesis testing.

Arthur has been an associate editor at IEEE Transactions on Pattern Analysis and Machine Intelligence, an Action Editor for JMLR, a Senior Area Chair for NeurIPS (2018,2021) and ICML (2022), a member of the COLT Program Committee in 2013, and a member of Royal Statistical Society Research Section Committee since January 2020. Arthur was program co-chair for AISTATS in 2016, tutorials co-chair for ICML 2018, workshops co-chair for ICML 2019, program co-chair for the Dali workshop in 2019, and co-organsier of the Machine Learning Summer School 2019 in London.
