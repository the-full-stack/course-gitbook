---
description: How to improve deep learning model?
---

# Improve

{% embed url="https://www.youtube.com/watch?v=rlFHwTE5qPE" caption="Improve - Troubleshooting" %}

## Summary

* The first step is to **address under-fitting:**
  * Add model complexity → Reduce regularization → Error analysis → Choose a more complex architecture → Tune hyper-parameters → Add features.
* The second step is to **address over-fitting:**
  * Add more training data → Add normalization → Add data augmentation → Increase regularization → Error analysis → Choose a more complex architecture → Tune hyper-parameters → Early stopping → Remove features → Reduce model size.
* The third step is to **address the distribution shift** present in the data:
  * Analyze test-validation errors and collect more training data to compensate.
  * Analyze test-validation errors and synthesize more training data to compensate.
  * Apply domain adaptation techniques to training and test distributions.
* The final step, if applicable, is to **rebalance your datasets:**
  * If the model performance on the test & validation set is significantly better than the performance on the test set, you over-fit to the validation set.
  * When it does happen, you can recollect the validation data by re-shuffling the test/validation split ratio.

