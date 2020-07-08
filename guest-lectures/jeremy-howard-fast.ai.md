---
description: >-
  Jeremy Howard is the co-founder of fast.ai, a research institute dedicated to
  making deep learning more accessible. Previously, Jeremy founded a med tech
  startup Enlitic, and was President of Kaggle.
---

# Jeremy Howard \(Fast.ai\)

{% embed url="https://www.youtube.com/watch?v=hZd3X\_nGdew" caption="Tricks To Train Deep Learning Models " %}

* Instead of automating the machine learning process, we should study how to augment it via **human-in-the-loop**.
* [Platform.ai](http://platform.ai) is a unique visual and code-free tool that labels images and trains computer vision models.
* Here are lessons learned from optimizing hyper-parameters for image datasets using [fast.ai](http://fast.ai):
  * Stick with a sensible learning rate \(most of the time, the default is good\).
  * With Test-Time Augmentation search, you can beat state-of-the-art results even if they use specialized models.
  * Progressive resizing is amazing.
  * Heatmaps are useful to visualize what's happening.
  * 1cycle is a big time-saver.
  * For transfer learning, always train later layers more: \(1\) gradual unfreezing and \(2\) discriminative learning rates.
  * Use AdamW optimizer.
  * If you are doing tons of epochs, consider clipping gradients or annealing Adam's episodes.

