---
title: "MARIN (MAven Research INterface)"
description: "Research software to study the Maven software ecosystem"
summary: "Research software to study the Maven software ecosystem"
order: 1
---
An interface focused on creating an accessible and scalable way to do research on artifacts on the Maven Central repository. MARIN contains an overarching implementation of the different modules in the interface, allowing for quick and repeated analysis runs to be performed.

Add the following dependency to your `pom.xml to add MARIN to your project:
```xml
<dependency>
    <groupId>eu.sse-labs</groupId>
    <artifactId>marin</artifactId>
    <version>1.0.0</version>
</dependency>
```

More info:
- [Our paper at MSR'25](https://doi.org/10.1109/MSR66628.2025.00093)

{{< github repo="sse-labs/marin" showThumbnail=true >}}