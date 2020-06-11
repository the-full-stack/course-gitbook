---
description: How to tune your model hyper-parameters?
---

# Hyperparameter Tuning

{% embed url="https://www.youtube.com/watch?v=n-2HeifoItU" caption="Hyperparameter Tuning - Infrastructure and Tooling" %}

## Summary

* Deep learning models are literally full of hyper-parameters. Finding the best configuration for these variables in a high-dimensional space is not trivial.
* Searching for hyper-parameters is an iterative process constrained by computing power, money, and time. Therefore, it would be really useful to have software that helps you search over hyper-parameter settings.
* **Hyperopt** is a Python library for serial and parallel optimization over awkward search spaces, which may include real-valued, discrete, and conditional dimensions.
* **SigOpt** is an optimization-as-a-service API that allows users to seamlessly tune the configuration parameters in AI and ML models.
* **Tune** is a Python library for hyper-parameter tuning at any scale, developed under the open-source project Ray.
* **Weights & Biases** has a nice feature called “Hyperparameter Sweeps” — a way to efficiently select the right model for a given dataset using the tool.

