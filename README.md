# ML4SCI - DeepLense Submission 2023

This repository contains the code for the DeepLense submission to ML4SCI for GSoC 2023.

1. [notebooks](notebooks) contains the notebooks for the tests and their results.
2. [models](models) contains the model weights.
3. [results](results) is used for storing the result images.

## Results

| Test | ROC-AUC Score | ROC Curve |
| ----------- | ------------- | --------- |
| Common Test | 0.9926442933333334 | <img src="results/common-test-roc-plot.png" alt="ROC plot" width="400" height="400"/> |
| Test 4 | 0.999952 | <img src="results/test-4-roc-plot.png" alt="ROC plot" width="400" height="400"/> |
| Test 5 - CvT | 0.99992 | <img src="results/test-5-cvt-roc-plot.png" alt="ROC plot" width="400" height="400"/> |
| Test 5 - CrossFormer | 0.99986 | <img src="results/test-5-crossformer-roc-plot.png" alt="ROC plot" width="400" height="400"/> |
| Test 5 - RegionViT | 0.9891319999999999 | <img src="results/test-5-regionvit-roc-plot.png" alt="ROC plot" width="400" height="400"/> |
| Test 2 | 0.9369537481702903 | <img src="results/test-2-roc-plot.png" alt="ROC plot" width="400" height="400"/> |
