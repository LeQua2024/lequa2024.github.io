---
layout: default
permalink: /data/
title: Data
---

## Data

The dataset **is now public** and accessible via [Zenodo](https://www.doi.org/10.5281/zenodo.5734465)!

The [data](https://www.doi.org/10.5281/zenodo.5734465) on which the tested systems will be required to operate consist of product reviews from the Amazon website. 
In Tasks 1A and 2A the label of each review is a sentiment-based polarity ("Positive" or "Negative", with "Positive" standing for all reviews marked 4 stars or higher and "Negative" standing for all reviews marked 2 stars or lower), while in Tasks 1B and 2B the label of each review will be the merchandise class (“Automotive”, “Baby”, "Beauty", ...) to which the product belongs. In all the above cases, the predictor will thus be asked to predict *how many* among the reviews in the test sample are about a given merchandise class, and to do this for all classes in the set.

This version of the [dataset](https://www.doi.org/10.5281/zenodo.5734465) consits of the training and validation splits for all four tasks. Test samples will be made available later on, as scheduled [here](https://lequa2022.github.io/timeline/).
In [GitHub](https://github.com/HLT-ISTI/LeQua2022_scripts) you will find detailed information regarding the dataset format, along with useful functions (written in Python) that would allow you to easily read, and iterate over, the data samples. This repository also contains a [format checker](https://github.com/HLT-ISTI/LeQua2022_scripts/blob/main/format_checker.py) to check that the format of your submissions is correct, and the official evaluation script that will be used on test samples one released (that you can already use on the development set in order to simulate the conditions of the evaluation phase).
