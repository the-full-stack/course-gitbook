---
description: How to effectively manage compute resources?
---

# Resource Management

{% embed url="https://www.youtube.com/watch?v=XmHRXktfwhM" caption="Resource Management - Infrastructure and Tooling" %}

## Summary

* Running complex deep learning models poses a very practical resource management problem: how to give every team the tools they need to train their models without requiring them to operate their own infrastructure?
* The most primitive approach is to use **spreadsheets** that allow people to reserve what resources they need to use.
* The next approach is to utilize a **SLURM Workload Manager**, a free and open-source job scheduler for Linux and Unix-like kernels.
* A very standard approach these days is to use Docker alongside Kubernetes.
  * **Docker** is a way to package up an entire dependency stack in a lighter-than-a-Virtual-Machine package.
  * **Kubernetes** is a way to run many Docker containers on top of a cluster.
* The last option is to use open-source projects.
  * Using **Kubeflow** allows you to run model training jobs at scale on containers with the same scalability of container orchestration that comes with Kubernetes.
  * **Polyaxon** is a self-service multi-user system, taking care of scheduling and managing jobs in order to make the best use of available cluster resources.

