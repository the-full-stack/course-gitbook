---
description: What are the components of a machine learning system?
---

# Overview

{% embed url="https://www.youtube.com/watch?v=\_pLe7\_b5tGc" caption="Overview - Infrastructure and Tooling" %}

## Summary

* Google's seminal paper "Machine Learning: The High-Interest Credit Card of Technical Debt" states that if we look at the whole machine learning system, the actual modeling code is very small. There are a lot of other code around it that configure the system, extract the data/features, test the model performance, manage processes/resources, and serve/deploy the model.
* The **data component:**
  * Data Storage - How to store the data?
  * Data Workflows - How to process the data?
  * Data Labeling - How to label the data?
  * Data Versioning - How to version the data?
* The **development component:**
  * Software Engineering - How to choose the proper engineering tools?
  * Frameworks - How to choose the right deep learning frameworks?
  * Distributed Training - How to train the models in a distributed fashion?
  * Resource Management - How to provision and mange distributed GPUs?
  * Experiment Management - How to manage and store model experiments?
  * Hyper-parameter Tuning - How to tune model hyper-parameters?
* The **deployment component**
  * Continuous Integration and Testing - How to not break things as models are updated?
  * Web - How to deploy models to web services?
  * Hardware and Mobile - How to deploy models to embedded and mobile systems?
  * Interchange - How to deploy models across systems?
  * Monitoring - How to monitor model predictions?
* All-In-One: There are solutions that handle all of these components!

