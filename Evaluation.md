---
layout: default
permalink: /evaluation/
title: Evaluation
---

## Evaluation 

- **Evaluation measures / scorer**
  - The performance of the predictors will be evaluated
    - (for Tasks T1, T2, T4): in terms of the RAE (relative absolute error) and AE (absolute error) measure; only RAE will be used for the final ranking, though;
    - (for Task T3): in terms of the NMD (Normalized Match Distance) measure, a special case of the Earth Mover Distance measure.
    The exact evaluation script that will be used to evaluate the participants submissions is available [here](https://github.com/HLT-ISTI/LeQua2024_scripts/blob/main/evaluate.py). Check [Fabrizio Sebastiani:
Evaluation measures for quantification: An axiomatic approach. Information Retrieval Journal 23(3): 255-288 (2020)](https://link.springer.com/article/10.1007/s10791-019-09363-y) for a thorough discussion of RAE, AE, and their suitability to evaluating quantification systems.
  - The test set will consist of a number of test samples (i.e., sets of documents), some of them characterized by prevalence values very different from the ones that chatacterize the training set; this is done in order to test the robustness of the quantifier to predict class prevalences very different from those it has been trained on. Check paper [Andrea Esuli, Alejandro Moreo, and Fabrizio Sebastiani. LeQua@CLEF2022: Learning to Quantify. Proceedings of the 44th European Conference on Information Retrieval (ECIR 2022), Stavanger, NO.](http://nmis.isti.cnr.it/sebastiani/LeQua2024.pdf) for a description of how the test samples have been generated
  - A scorer that reflects how the evaluation is carried out will be released to participants by December 1, 2021.
- **Tools and baselines**
  - A number of baseline (and advanced) methods for learning to quantify are implemented in the [QuaPy](https://github.com/HLT-ISTI/QuaPy/tree/lequa2024) Python-based, open-source library, which also contains implementations of standard evaluation measures and evaluation protocols. For participating in this lab you are welcome to use [QuaPy](https://github.com/HLT-ISTI/QuaPy/tree/lequa2024) and its tools in any way you might deem suitable. Check paper [Alejandro Moreo, Andrea Esuli, and Fabrizio Sebastiani. QuaPy: A Python-based framework for quantification. Proceedings of the 30th ACM International Conference on Knowledge Management (CIKM 2021), Gold Coast, AU, pp. 4534–4543.](https://dl.acm.org/doi/10.1145/3459637.3482015) to learn more about QuaPy.
- **Required format for submissions**
  - A [format checker](https://github.com/HLT-ISTI/LeQua2024_scripts) and a [dummy submission](https://doi.org/10.5281/zenodo.5734464) are made available to participant teams.
