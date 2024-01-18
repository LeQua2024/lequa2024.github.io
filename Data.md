---
layout: default
permalink: /data/
title: Data
---

## Data

<!-- BEGIN COMMENTED BLOCK
The dataset **is now public** and accessible via [Zenodo](https://doi.org/10.5281/zenodo.5734464)!
END COMMENTED BLOCK -->

The data on which the tested systems will be required to operate consist of product reviews from the Amazon website, already converted in vector form. 

* In Tasks T1 and T4 the class label of each review is a sentiment-based polarity ("Positive" or "Negative", with "Positive" standing for all reviews marked "4 stars" or higher and "Negative" standing for all reviews marked "2 stars" or lower).

* In Task T2 the class label of each review is the merchandise class (“Automotive”, “Baby”, "Beauty", ...) to which the product belongs.

* In Task T3 the class label of each review is the original sentiment-based polarity, expressed as a star rating (from "1 stars" to "5 stars").

In all the above cases, the predictor will thus be asked to predict *how many* among the reviews in the test sample have a certain class label, and to do this for all classes in the set.

The data provided to participants by Feb 15, 2024 will consist of the training set and the validation samples for all four tasks. By May 1 participants will be provided with the samples of unlabelled datapoints. 
In [GitHub](https://github.com/HLT-ISTI/LeQua2024_scripts) participants will find detailed information regarding the dataset format, along with useful functions (written in Python) allowing to easily read, and iterate over, the data samples. This repository also contains a [format checker](https://github.com/HLT-ISTI/LeQua2024_scripts/blob/main/format_checker.py) allowing to check that the format of a submissions is correct, and the official evaluation script that will be used on test samples once these are released (and that can be used on the development samples in order to simulate the conditions of the evaluation phase).
