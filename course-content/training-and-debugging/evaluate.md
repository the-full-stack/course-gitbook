---
description: How to evaluate deep learning model?
---

# Evaluate

{% embed url="https://www.youtube.com/watch?v=wP6BkXcB\_Xg" caption="Evaluate - Troubleshooting" %}

## Summary

* You want to apply **the bias-variance decomposition** concept here: _Test error = irreducible error + bias + variance + validation overfitting_.
* If the training, validation, and test sets come from different data distributions, then you should use **2 validation sets**: one set sampled from the training distribution, and the other set sampled from the test distribution.

⇒ _Test error = irreducible error + bias + variance + distribution shift + validation overfitting_

