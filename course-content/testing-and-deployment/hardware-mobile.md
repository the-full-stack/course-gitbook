---
description: How to deploy your models to hardware and mobile devices?
---

# Hardware/Mobile

{% embed url="https://youtu.be/uq6soVz\_IuU" caption="Hardware and Mobile - Testing and Deployment" %}

## Summary

* Embedded and mobile devices have low-processor with little memory, which makes the process slow and expensive to compute. Often, we can try some tricks such as reducing network size, quantizing the weights, and distilling knowledge.
  * Both **pruning** and **quantization** are model compression techniques that make the model physically smaller to save disk space and make the model require less memory during computation to run faster.
  * **Knowledge distillation** is a compression technique in which a small “student” model is trained to reproduce the behavior of a large “teacher” model.
* Embedded and mobile PyTorch/TensorFlow frameworks are less fully featured than the full PyTorch/TensorFlow frameworks. Therefore, we have to be careful with the model architecture. An alternative option is using the interchange format.
  * **Mobile machine learning frameworks** are regularly in flux: Tensorflow Lite, PyTorch Mobile, CoreML, MLKit, FritzAI.
  * The best solution in the industry for **embedded** devices is NVIDIA.
  * The **Open Neural Network Exchange** \(ONNX for short\) is designed to allow framework interoperability.

