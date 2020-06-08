---
description: How do you pick metrics to optimize for your machine learning project?
---

# Metrics

{% embed url="https://www.youtube.com/watch?v=-US7jrlz3wM" %}

* In most real-world projects, you usually care about a lot of metrics. Because machine learning systems work best when optimizing a single number, you need to pick a formula for combining different metrics of interest.
* The first way is to do a simple **average** \(or **weighted average**\) of these metrics.
* The second way is to choose a metric as a **threshold** and evaluate at that threshold value. The thresholding metrics are up to your domain judgment, but you would probably want to choose ones that are least sensitive to model choice and are closest to desirable values.
* The third way is to use a more **complex / domain-specific** formula. A solid process to go about this direction is to first start enumerating all the project requirements, then evaluate the current performance of your model, then compare the current performance to the requirements, and finally revisit the metric as your numbers improve.



