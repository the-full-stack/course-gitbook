---
description: What are appropriate ways to store your data?
---

# Storage

{% embed url="https://www.youtube.com/watch?v=HUYDy3NZkHU" caption="Storage - Data Management" %}

## Summary

* Data storage requirements for AI vary widely according to the application and the source material.
* The **filesystem** is the foundational layer of storage. Its fundamental unit is a “file” — which can be text or binary, is not versioned, and is easily overwritten.
* **Object storage** is an API over the filesystem that allows users to use a command on files \(GET, PUT, DELETE\) to a service, without worrying where they are actually stored. Its fundamental unit is an “object” — which is usually binary \(images, sound files…\).
* The **database** is a persistent, fast, and scalable storage/retrieval of structured data. Its fundamental unit is a “row” \(unique IDs, references to other rows, values in columns\).
* A **data lake** is the unstructured aggregation of data from multiple sources \(databases, logs, expensive data transformations\). It operates under the concept of “schema-on-read” by dumping everything in and then transforming the data for specific needs later.

