---
description: >-
  Yangqing is currently the VP AI / Big Data at Alibaba, and was formerly
  Director of AI Platform at Facebook. He co-created the Caffe2 and Caffe deep
  learning frameworks.
---

# Yangqing Jia \(Alibaba\)

{% embed url="https://youtu.be/s2MWUamDYUI" caption="What\'d Ya Mean by Frameworks?" %}

### The Progress of Deep Learning Frameworks

* 2008: Theano
* 2012: Torch7
* 2013: Caffe
* 2015: Keras, TensorFlow
* 2017: Caffe2, PyTorch, ONNX

### What Are The Deciding Factors?

* A framework is intended for model development.
* A framework helps to improve **developer efficiency -** trying out ideas faster \(debugging, interactive development, simplicity, intuitiveness\).
* A framework helps to improve **infrastructure efficiency -** running computation faster \(implementation, scalability, model definition, cross-platform requirements\).
* A good framework makes a **balance** between developer efficiency and infrastructure efficiency.

#### Declarative Toolkits

* Examples include Theano, Caffe, MXNet, TensorFlow, and Caffe2.
* In these frameworks, we declare and compile models, then repeatedly execute the models in a Virtual Machine.
* **Advantages**:
  * Easy to optimize.
  * Easy to serialize for production deployment.
* **Disadvantages**:
  * Non-intuitive programming model.
  * Difficult to design and maintain.

#### Imperative Toolkits

* Examples include PyTorch and Chainer.
* In these frameworks, we define and construct the models by running computation. There is no separate execution engine.
* **Advantages**:
  * Intuitive to write programs.
  * Easy to design, debug, and iterate.
* **Disadvantages**:
  * Difficult to optimize - no domain-specific languages.
  * Hard to deploy on multiple platforms.

#### Facebook Example

* Research to Production at Facebook:
  * PyTorch → Caffe2 \(2017\): Reimplementation took weeks or months.
  * PyTorch → ONNX → Caffe2 \(2018\): Enabling model or model fragment transfer.
  * PyTorch + Caffe2 \(2019-Present\): Combining both the advantages of developer efficiency and infrastructure efficiency.
* Many frameworks start adopting such a combination:
  * Keras/TF-Eager + TensorFlow
  * Gluon + MXNet

### How To Choose Frameworks

* Understand your **need**:
  * Developer Efficiency: Algorithm Research? Startup? Proof of Concept?
  * Infrastructure Efficiency: System Research? Cross-Platform? Scale?
* Learn one framework and **focus on your problem**.
* It's fine to switch.
* The goal of frameworks is to improve **productivity.**

### Beyond Frameworks

* Within the tech stack, there is the **libraries** layer on top of frameworks: TF-Serving, CoreML, Clipper, Ray, etc.
* On top of libraries, we have the **applications** layer: Detectron, FairSeq, Magenta, GluonNLP, etc.
* Below the frameworks, we have the layer of **runtime, compilers, and optimizers**: CuDNN, NNPack, TVM, ONXX, etc.
* The lowest layer is **hardware:** CPU, GPU, DSP, FPGA/ASIC

### Thoughts Across The Stack

* Do NOT use AlexNet!
* Unifications help everyone: ONNX bridges the gap between high-level API & framework frontends with hardware vendor libraries & devices.
* Invest in experiment management.
* Use Computer Science conventional wisdom: programming language, compilers, scientific computation, databases, etc.
* Things change across the stack:
  * Applications layer: quantization brings a balance between speed and accuracy.
  * Libraries layer: auto-quantization interfaces increase ease of use.
  * Frameworks layer: quantized training, auto-scaling, etc.
  * Runtime, compilers, optimizers layer: high-performance fixed-point math.
  * Hardware layer: quantized computation primitives.

