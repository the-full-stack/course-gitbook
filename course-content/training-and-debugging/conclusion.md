---
description: What are the key takeaways to troubleshoot deep neural networks?
---

# Conclusion

{% embed url="https://www.youtube.com/watch?v=Ja414543TBM" caption="Conclusion - Troubleshooting" %}

## Summary

* Deep learning debugging is hard due to many competing sources of error.
* To train bug-free deep learning models, you need to treat building them as an iterative process.
  * Choose the simplest model and data possible.
  * Once the model runs, overfit a single batch and reproduce a known result.
  * Apply the bias-variance decomposition to decide what to do next.
  * Use coarse-to-fine random searches to tune the model’s hyper-parameters.
  * Make your model bigger if your model under-fits and add more data and/or regularization if your model over-fits.

