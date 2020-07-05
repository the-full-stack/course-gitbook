---
description: >-
  Co-founder and CTO at Curai. Previously: VP of Engineering at Quora, led
  Algorithms Engineering at Netflix.
---

# Xavier Amatriain \(Curai\)

{% embed url="https://youtu.be/5ygO8FxNB8c" caption="Lessons Learned From Building Practice Deep Learning Systems" %}

### Lesson 1 - More Data or Better Models?

* **More data** is preferred when we have access to more features and our models have low-bias.
* **Better models** is preferred when the space of our feature set has low dimensions.
* **Transfer learning** lowers the need for access to data. In order to use this method effectively, we want to **fine-tune** the pre-trained models on **better data.**

### Lesson 2 - Simple Models &gt;&gt;&gt; Complex Models

* **Occam's Razor:** Given two models that perform more or less equally, you should always prefer the less complex.
* Deep learning might not be preferred, even if it squeezes an increase of 1% accuracy.
* Reasons to use simple models include scalability, system complexity, maintenance, explainability, etc.

### Lesson 3 - Sometimes, You Need Complex Models

* More complex features may require a more complex model.
* A more complex model may not show improvements with a feature set that is too simple.

### Lesson 4 - You Should Care About Feature Engineering

* A **well-behaved** Machine Learning feature should be reusable, transformable, interpretable, and reliable.
* In deep learning, **architecture engineering** is the new feature engineering.

### Lesson 5 - Supervised vs Unsupervised Learning

* Most fascinating results in recent years come from **a combination** of the two approaches \(stacked autoencoders, unsupervised pre-training, etc.\).
* **Self-supervised learning** is a learning paradigm where we train a model using labels that are naturally part of the input data, rather than requiring separate external labels.

