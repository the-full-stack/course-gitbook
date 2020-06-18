---
description: How to implement and debug deep learning models?
---

# Debug

{% embed url="https://www.youtube.com/watch?v=d07le7otRUM" caption="Debug - Troubleshooting" %}

## Summary

* The 5 most common bugs in deep learning models include:
  * Incorrect shapes for tensors.
  * Pre-processing inputs incorrectly.
  * Incorrect input to the loss function.
  * Forgot to set up train mode for the network correctly.
  * Numerical instability - inf/NaN.
* 3 pieces of general advice for implementing models:
  * Start with **a lightweight implementation**.
  * Use **off-the-shelf components** such as Keras if possible, since most of the stuff in Keras works well out-of-the-box.
  * Build **complicated data pipelines later**.
* The first step is to **get the model to run**:
  * For **shape mismatch and casting issues**, you should step through your model creation and inference step-by-step in a debugger, checking for correct shapes and data types of your tensors.
  * For **out-of-memory issues**, you can scale back your memory-intensive operations one-by-one.
  * For **other issues**, simply Google it. StackOverflow would be great most of the time.
* The second step is to have the model **overfit a single batch**:
  * **Error goes up:** Commonly this is due to a flip sign somewhere in the loss function/gradient.
  * **Error explodes:** This is usually a numerical issue, but can also be caused by a high learning rate.
  * **Error oscillates:** You can lower the learning rate and inspect the data for shuffled labels or incorrect data augmentation.
  * **Error plateaus:** You can increase the learning rate and get rid of regulation. Then you can inspect the loss function and the data pipeline for correctness.
* The third step is to **compare the model to a known result**:
  * The most useful results come from **an official model implementation** **evaluated on a similar dataset to yours**.
  * If you can’t find an official implementation on a similar dataset, you can compare your approach to results from **an official model implementation evaluated on a benchmark dataset**.
  * If there is no official implementation of your approach, you can compare it to results from **an unofficial model implementation**.
  * Then, you can compare to results from **a paper with no code**, results from **the model on a benchmark dataset**, and results from **a similar model on a similar dataset**.
  * An under-rated source of results come from **simple baselines**, which can help make sure that your model is learning anything at all.

