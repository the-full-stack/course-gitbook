---
description: How to deploy your models to the web?
---

# Web Deployment

{% embed url="https://youtu.be/1BegV7gjqDo" caption="Web Deployment - Testing and Deployment" %}

## Summary

* For web deployment, you need to be familiar with the concept of **REST API.**
  * You can deploy the code to Virtual Machines, and then scale by adding instances.
  * You can deploy the code as containers, and then scale via orchestration.
  * You can deploy the code as a “server-less function.”
  * You can deploy the code via a model serving solution.
* If you are making **CPU inference**, you can get away with scaling by launching more servers \(Docker\), or going serverless \(AWS Lambda\).
* If you are using **GPU inference**, things like TF Serving and Clipper become useful with features such as adaptive batching.

