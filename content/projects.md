---
title: "Projects"
date: 2023-08-25T09:27:47+02:00
---

**Model Multiplicity in Policy Learning** 

In policy learning, treatment rules are learned that map individual characteristics to treatment recommendations, aiding decision-making in fields like healthcare, education, and public policy. Policy rules are determined by choosing the model that performs best on training data, neglecting the issue of model multiplicity. Model multiplicity arises when multiple models are indistinguishable in terms of estimated performance but differ in structure and predictions. We introduce the concept of model multiplicity to the policy learning literature, along with formal measures to quantify its extent and individual-level welfare costs. Our integer programming approach is demonstrated with synthetic data and applied to two real-world scenarios: allocating individuals to training programs and prescribing tranexamic acid to trauma patients. We find model multiplicity and indication for adverse effects, calling into question the current practice of model selection in policy learning. We conclude that additional criteria for model selection need to be established if policy learning is to be deployed in high-stake applications where model multiplicity raises ethical and legal concerns.

*Keywords— policy learning, data-driven decision making, heterogeneous treatment effects, model multiplicity, mixed-integer optimization* 

Working Paper available upon request. 

**Optimal Policy Learning in Empirical Practice**
joint with Michael Lechner

This paper reviews, applies, and extends recently proposed methods for learning data-driven decision rules that exploit treatment effect heterogeneities. We juxtapose interpretable decision systems with black-box models, elucidating the trade-offs regarding explainability, vulnerability to misspecification, and computational complexity. We illustrate the application of policy learning methods through an assessment of training programmes. Our results offer practical insights for decision makers in pursuit of performant and trustworthy decision-making tools.

Keywords— policy learning, data-driven decision making, heterogeneous treatment effects, mixed-integer optimization, neural networks

Working Paper available upon request. 

**Climate Risk Beliefs and Extreme Weather Events**

We revisit the question of if and how agents update their climate risk perceptions against the backdrop of extreme weather events. The study combines 20 years of geo-located panel data with insurance and climate data. We find that community damage prompts individuals to update their risk perceptions. Drawing from causal machine learning, we find meaningful effect heterogeneity for groups as defined by prior political and climate risk attitudes, which is consistent with a theory of directed motivational reasoning.

**High Resolution Treatment Effects Estimation: Uncovering Effect Heterogeneities with the Modified Causal Forest**
joint with Hugo Bodory and Michael Lechner

There is great demand for inferring causal effect heterogeneity and for open-source statistical software, which is readily available for practitioners. The mcf package is an open-source Python package that implements Modified Causal Forest (mcf), a causal machine learner. We replicate three well-known studies in the fields of epidemiology, medicine, and labor economics to demonstrate that our mcf package produces aggregate treatment effects, which align with previous results, and in addition, provides novel insights on causal effect heterogeneity. For all resolutions of treatment effects estimation, which can be identified, the mcf package provides inference. We conclude that the mcf constitutes a practical and extensive tool for a modern causal heterogeneous effects analysis.
