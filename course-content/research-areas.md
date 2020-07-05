---
description: >-
  Professor Pieter Abbeel covers state of the art deep learning methods that are
  just now becoming usable in production.
---

# Research Areas

{% embed url="https://youtu.be/OMraS0GRWK0" caption="Research Areas" %}

## A Sampling of Research Directions

### Few-Shot Learning

* **Model-Agnostic Meta-Learning** is an end-to-end learning paradigm of a parameter vector that is a good initialization for fine-tuning many tasks.
* It works well for classification problems, optimization tasks, and generative models.

### Reinforcement Learning

* Compared to supervised learning, reinforcement learning has additional challenges in terms of **credit assignment, stability,** and **exploration**.
* Success stories of reinforcement learning are predominantly in the domains of **game-playing** and **robotics**.
* **Meta-Reinforcement Learning** helps us \*\*develop "fast" reinforcement learning algorithms that can adapt to real-world scenarios.
* **Multi-Armed Bandits** is a solid evaluation scheme for reinforcement learning methods.
* **Contextual Bandits** is basically a simpler version of reinforcement learning with no states.
* In **the real world**, reinforcement learning works well whenever we have a great simulator/demonstration of the environment and an inexpensive data collection process.

### Imitation Learning

* In the **imitation learning** paradigm, we collect many demonstrations and turn them into a policy that can interact with the environment.
* **One-Shot Imitation Learning** only needs a single demonstration of a new task to figure out the next action.
* In **the real world,** imitation learning works well whenever we have access to previous data and it's easy to predict what happens next.

### Domain Randomization

* The motivation here is **how can we learn useful real-world skills in the simulator?**
* **Domain randomization** operates under the assumption that if the model sees enough simulated variation, the real world may look like just the next simulator.
* A well-known example is the **OpenAI's robot hand** that solves the Rubik Cube.

### Architecture Search

* The idea behind **architecture search** is to use search algorithms to determine the optimal architecture for our neural networks.
* We can use reinforcement learning to perform this search process.
* Small architectures sometimes match the performance of the bigger architectures.
* Furthermore, we can use reinforcement learning to design the right **data augmentation** scheme to maximize performance.

### Unsupervised Learning

* **Unsupervised learning** deals with unlabeled data. We can learn the network that embeds the data or learn the weights of the network architecture.
* The main families of models include Variational Autoencoders, Generative Adversarial Networks, Exact Likelihood Models, and "puzzles" ones.
* **Contrastive Predictive Coding** is an unsupervised learning scheme that breaks up the input into pieces, removes specific pieces, and asks the network to fill those pieces back in the final output.
* A well-known example is the **OpenAI's GPT-2 system** that can generate text.

## Overall Research Theme

* Researchers use more computing power to get better results.
* You should focus on problem territory with a lot of **data** and **compute** than human ingenuity.

## Bridge The Research and Real-World Gap

* **Research** is about going from 0 to 1.
* In **real-world** applications, often 90% performance is not enough.

## How To Keep Up

* Learn to read academic papers.
* Helpful resources to get papers are Import AI newsletter, Arxiv Sanity, Twitter, Facebook Groups, and ML Subreddit.
* Form a reading group.

