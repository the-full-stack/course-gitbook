---
description: >-
  Co-founder and CTO at Curai. Previously: VP of Engineering at Quora, led
  Algorithms Engineering at Netflix.
---

# Xavier Amatriain \(Curai\)

{% embed url="https://youtu.be/5ygO8FxNB8c" caption="Lessons Learned From Building Practical Deep Learning Systems" %}

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

### Lesson 6 - Everything is an Ensemble

* Most practical applications of machine learning run an **ensemble**. You can use completely different approaches at the ensemble layer.
* Ensemble resembles the way to turn any model into a feature!

### Lesson 7 - There are Biases in Your Data

* **Biases** can happen in the data labels, or even in the presentation to end-users.
* Introducing biases leads to a lack of **fairness** in machine learning.

### Lesson 8 - Think About Models "In the Wild"

* Two desired properties of models in the wild are:
  * **Easily extensible**: incrementally/iteratively learn from "human-in-the-loop" or from additional data.
  * **Knows what it does not know**: model uncertainty in prediction and enable fall-back to manual.

### Lesson 9 - Choose The Right Evaluation Approach

* Evaluation metrics used during **offline** and **online** experiments must match!
* **A/B tests** help measure differences in metrics across statistically identical populations that each experience a different algorithm.
* Use **long-term metrics** whenever possible.
* **Short-term metrics** can be informative and allow faster decisions.

### Lesson 10 - Do Not Underestimate the Value of Systems and Frameworks

* You should apply the best **software engineering** practices during the design of machine learning systems \(encapsulation, abstraction, cohesion, low coupling, etc.\).
* However, **design patterns** for machine learning software are not well-known or documented.

### Lesson 11 - Your Machine Learning Infrastructure Will Have Two Masters

* Whenever you develop any ML infrastructure, you need to target two different modes:
  * **ML experimentation** that emphasizes flexibility, reusability, and ease of use.
  * **ML production** that adds on a new layer of performance and scalability.
* In order to combine them:
  * Research should be done using tools that are the same in production.
  * Abstraction layers should be implemented on top of the optimized research code so they can be accessed from friendly experimentation tools.

### Lesson 12 - There is Machine Learning Beyond Deep Learning

* Examples of other ML approaches include XGBoost, tensor methods, factorization machines, non-parametric Bayesian methods, etc.
* Sometimes, deep learning methods do not outperform these simpler approaches.

