---
layout: default
permalink: /data/
title: Data
---

## Data

The dataset **is now public** and accessible via [Zenodo](https://doi.org/10.5281/zenodo.10654474)!

The data on which the tested systems are required to operate consist of product reviews from the Amazon website, already converted in vector form. 

* In Tasks T1 and T4 (both binary tasks) the class label of each review is a binary sentiment-based polarity ("Positive" or "Negative", with "Positive" standing for all reviews marked "4 stars" or higher and "Negative" standing for all reviews marked "2 stars" or lower).

* In Task T2 the class label of each review is the merchandise class (“Automotive”, “Baby”, "Beauty", ...) to which the product belongs.

* In Task T3 the class label of each review is the original sentiment-based polarity, expressed as a star rating (from "1 stars" to "5 stars").

In all the above cases, the predictor is thus asked to predict *how many* among the reviews in the test sample have a certain class label, and to do this for all the classes in the set.

This version of the [dataset](https://doi.org/10.5281/zenodo.10654474) consits of the training and validation splits for all four tasks. By May 1 participants will be provided with the samples of the unlabelled (test) datapoints. 
In [GitHub](https://github.com/HLT-ISTI/LeQua2024_scripts) participants may find detailed information regarding the dataset format, along with useful functions (written in Python) allowing to easily read, and iterate over, the data samples. This repository also contains a [format checker](https://github.com/HLT-ISTI/LeQua2024_scripts/blob/main/format_checker.py) allowing to check that the format of a submission is correct, and the official [evaluation script](https://github.com/HLT-ISTI/LeQua2024_scripts/blob/main/evaluate.py) that will be used on test samples once these are released (and that can be used on the development samples in order to simulate the conditions of the evaluation phase).
