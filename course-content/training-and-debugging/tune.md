---
description: How to tune deep learning model?
---

# Tune

{% embed url="https://www.youtube.com/watch?v=8jhKNAHVfno" caption="Tune - Troubleshooting" %}

## Summary

* Choosing which hyper-parameters to optimize is not an easy task since some are more sensitive than others and are dependent upon the choice of model.
  * **Low sensitivity**: Optimizer, batch size, non-linearity.
  * **Medium sensitivity**: weight initialization, model depth, layer parameters, weight of regularization.
  * **High sensitivity**: learning rate, annealing schedule, loss function, layer size.
* Method 1 is **manual optimization:**
  * For a skilled practitioner, this may require the least amount of computation to get good results.
  * However, the method is time-consuming and requires a detailed understanding of the algorithm.
* Method 2 is **grid search:**
  * Grid search is super simple to implement and can produce good results.
  * Unfortunately, it’s not very efficient since we need to train the model on all cross-combinations of the hyper-parameters. It also requires prior knowledge about the parameters to get good results.
* Method 3 is **random search:**
  * Random search is also easy to implement and often produces better results than grid search.
  * But it is not very interpretable and may also require prior knowledge about the parameters to get good results.
* Method 4 is **coarse-to-fine search:**
  * This strategy helps you narrow in only on very high performing hyper-parameters and is a common practice in the industry.
  * The only drawback is that it is somewhat a manual process.
* Method 5 is **Bayesian optimization search:**
  * Bayesian optimization is generally the most efficient hands-off way to choose hyper-parameters.
  * But it’s difficult to implement from scratch and can be hard to integrate with off-the-shelf tools.

