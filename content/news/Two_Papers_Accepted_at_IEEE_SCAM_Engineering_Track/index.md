---
guid: "news-12836"
pubDate: "Wed, 08 Sep 2021 10:29:22 +0200"
title: "Two Papers Accepted at IEEE SCAM Engineering Track"
link: "https://sse.cs.tu-dortmund.de/newsdetail/two-papers-accepted-at-ieee-scam-engineering-track-12836/"
enclosure: ""
source: "Two Papers Accepted at IEEE SCAM Engineering Track"
summary: "We share insights into our design decisions and our handling of globals in C/C++ programs."
featured_image: "/featured.png"
---
![Two Papers Accepted at IEEE SCAM Engineering Track](/featured.png)

PhASAR is our static data-flow analysis framework written in C++ for the analysis of C/C++ programs. It is based on the LLVM infrastructure. Due to the unique feature of the C/C++ language family such as arbitrary pointers to memory, and unsafe type systems, or multiple inheritance static program analysis for this language family poses a unique challenge. We open-sourced PhASAR in 2018 and since then have received numerous issues and pull requests from academia and industry. It currently has over 600 stars on GitHub.

In the first paper we share the key mistakes we made in the first years of PhASAR as well as our stategies to correct them and come to a more reliable architecture for the framework. We derive some guidelines for the development of future static analysis frameworks.

In the second paper we share our strategies for modelling global variables in an analysis. This is necessary despite that global variable are disencouraged because in real-world code they are still used. They pose a particular challenge for analyses as they may be used to leak information and therefore may influence control flow. Our modelling can of course be used outside of PhASAR as well and may lead to a more sound interpretation of the effects of those variables.

Both papers have been accepted at the Engineering track at the 21st IEEE International Working Conference on Source Code Analysis and Manipulation (SCAM). It is an annual conference on the analysis of source code and derivatives (e.g. bytecode). In this edition a strong emphasis was given on open science with an adjoint artifact track. As PhASAR is already open source we were well-prepared and happy to submit to SCAM.
