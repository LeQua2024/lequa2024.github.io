---
layout: default
permalink: /evaluation/
title: Evaluation
---

## Evaluation 

- **Required format for submissions**
  - A format checker and a dummy submission will be provided to participant teams
- **Tools and baselines**
  - A number of baseline (and advanced) methods for learning to quantify are implemented in the [QuaPy](https://pypi.org/project/QuaPy/) Python-based, open-source library, which also contains implementations of standard evaluation measures and evaluation protocols. For participating in this lab you are welcome to use [QuaPy](https://pypi.org/project/QuaPy/) and its tools in any way you might deem suitable.
- **Evaluation measures / scorer**
  - The performance of the predictors will be evaluated in terms of the AE (absolute error) and RAE (relative absolute error) measure; only AE will be used for the final ranking, though. Check [Fabrizio Sebastiani:
Evaluation measures for quantification: An axiomatic approach. Information Retrieval Journal 23(3): 255-288 (2020)](https://link.springer.com/article/10.1007/s10791-019-09363-y) for a thorough discussion of AE, RAE, and their suitability to evaluating quantification systems.
  - The test set will consist of a number of test samples (i.e., sets of documents), some of them characterized by prevalence values very different from the ones that chatacterize the training set; this is done in order to test the robustness of the quantifier to predict class prevalences very different from those it has been trained on.
  - A scorer that reflects how the evaluation is carried out will be released to participants.
