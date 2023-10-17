---
layout: page
permalink: /research/
title: research
description:
nav: true
nav_order: 1
---

My research is primarily centered on the methodology of missing data with applications to Alzheimer’s disease research. In my work, I develop some theory behind missing data methods and explore new modeling strategies including extensions to missing not at random (MNAR) assumptions. Some of my PhD research projects are included below:

**Latent variable models applied to Alzheimer's disease data with missing data**

Multivariate bounded discrete data arises in many fields. In the setting of longitudinal dementia studies, such data is collected when individuals complete neuropsychological tests. We outline a modeling and inference procedure that can model the joint distribution conditional on baseline covariates, leveraging previous work on mixtures of experts and latent class models. Furthermore, we illustrate how the work can be extended when the outcome data is missing at random using a nested EM algorithm. The proposed model can incorporate covariate information, perform imputation and clustering, and infer latent trajectories. We apply our model on simulated data and an Alzheimer's disease data set.

[[Preprint]](https://arxiv.org/abs/2310.09384) [[R package]](https://github.com/danielsuen/mixturebpe)

**Multistage estimators for missing covariates and incomplete outcomes**

We study problems with multiple missing covariates and partially observed responses. We develop a new framework to handle complex missing covariate scenarios via inverse probability weighting, regression adjustment, and a multiply-robust procedure. We apply our framework to three classical problems: the Cox model from survival analysis, missing response, and binary treatment from causal inference. We also discuss how to handle missing covariates in these scenarios, and develop associated identifying theories and asymptotic theories. We apply our procedure to simulations and an Alzheimer's disease dataset and obtain meaningful results. 

[[Preprint]](https://arxiv.org/abs/2111.02367)