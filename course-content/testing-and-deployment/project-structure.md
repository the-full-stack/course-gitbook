---
description: What are the different components of a machine learning system?
---

# Project Structure

{% embed url="https://youtu.be/uctx9L0tuCc" caption="Project Structure - Testing and Deployment" %}

## Summary

* The **prediction system** involves code to process input data, to construct networks with trained weights, and to make predictions.
* The **training system** processes raw data, runs experiments, and manages results.
* The goal of any prediction system is to be deployed into the **serving system**. Its purpose is to serve predictions and to scale to demand.
* **Training and validation data** are used in conjunction with the training system to generate the prediction system.
* At production time, we have **production data** that has not been seen before and can only be served by the serving system.
* The prediction system should be tested by **functionality** to catch code regressions and by **validation** to catch model regressions.
* The training system should have its tests to catch upstream regressions \(change in data sources, upgrade of dependencies\)
* For production data, we need **monitoring** that raises alert to downtime, errors, distribution shifts, etc. and catches service and data regressions.

