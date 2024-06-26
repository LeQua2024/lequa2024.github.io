---
layout: default
permalink: /evaluation/
title: Evaluation
---

## Evaluation 

- **Evaluation measures / scorer**
  - The performance of the predictors will be evaluated
    - (for Tasks T1, T2, T4): in terms of the RAE (relative absolute error) and AE (absolute error) measures; only RAE will be used for the final ranking, though;
    - (for Task T3): in terms of NMD (Normalized Match Distance), a special case of the Earth Mover's Distance. We consider two variants of NMD: the classical mean NMD (MNMD), and the "macro-NMD"; only MNMD will be used for the final ranking, though.
    The evaluation script that will be used to evaluate the participants' submissions will be made available [here](https://github.com/HLT-ISTI/LeQua2024_scripts/blob/main/evaluate.py) by Feb 15 2024. Check Chapter 3 of this [(open-access) book](https://link.springer.com/book/10.1007/978-3-031-20467-8) for a thorough discussion of RAE, AE, NMD, and their suitability to evaluating quantification systems.
  - The test set will consist of a number of test samples (i.e., sets of documents), some of them characterized by prior probability shift (T1, T2, T3) or covariate shift (T4); this is done in order to test the robustness of the quantifier to predict class prevalence values under conditions different from those it has been trained on.
- **Tools and baselines**
  - A number of baseline (and advanced) methods for learning to quantify are implemented in the [QuaPy](https://github.com/HLT-ISTI/QuaPy/tree/lequa2024) Python-based, open-source library. For participating in LeQua 2024 you are welcome to use [QuaPy](https://github.com/HLT-ISTI/QuaPy/tree/lequa2024) and its tools in any way you might deem suitable. Check paper [Alejandro Moreo, Andrea Esuli, and Fabrizio Sebastiani. QuaPy: A Python-based framework for quantification. Proceedings of the 30th ACM International Conference on Knowledge Management (CIKM 2021), Gold Coast, AU, pp. 4534–4543.](https://dl.acm.org/doi/10.1145/3459637.3482015) to learn more about QuaPy.
- **Required format for submissions**
  - A [format checker](https://github.com/HLT-ISTI/LeQua2024_scripts) and a [dummy submission](https://doi.org/10.5281/zenodo.10654474) are available.
