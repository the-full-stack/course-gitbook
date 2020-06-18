---
description: >-
  How to choose a deep learning framework? How to enable distributed training
  for your models?
---

# Frameworks and Distributed Training

{% embed url="https://www.youtube.com/watch?v=vlwf7wEVoW4" caption="Frameworks and Distributed Training - Infrastructure and Tooling" %}

## Summary

* Unless you have a good reason not to, you should use either **TensorFlow** or **PyTorch**.
* Both frameworks are converging to a point where they are good for research and production.
* [**fast.ai**](http://fast.ai) is a solid option for beginners who want to iterate quickly.
* Distributed training of neural networks can be approached in 2 ways: \(1\) data parallelism and \(2\) model parallelism.
* Practically, **data parallelism** is more popular and frequently employed in large organizations for executing production-level deep learning algorithms.
* **Model parallelism**, on the other hand, is only necessary when a model does not fit on a single GPU.
* **Ray** is an open-source project for effortless, stateful, parallel, and distributed computing in Python.
* **Horovod** is Uber’s open-source distributed deep learning framework that uses a standard multi-process communication framework, so it can be an easier experience for multi-node training.

