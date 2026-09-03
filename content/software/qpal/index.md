---
title: "QPAL"
description: "QPAL - Quantum Program Analysis Library"
summary: "Rust-based static program analysis for QASM programs"
order: 2
---

QPal is a high-performance, Rust-based static analysis framework for quantum circuits. Built to overcome the exponential scaling limits of classical simulation, QPal is capable of processing massive quantum programs efficiently.
  
By parsing OpenQASM 3 source code, QPal abstracts and compresses circuits without altering their quantum behavior. It accomplishes this by identifying and extracting recurring subcircuits (code clones) into supergates, significantly reducing the topological depth and node complexity of the circuit. This compression enables downstream static analysis tools to operate on a vastly simplified, yet functionally equivalent, circuit graph.


{{< github repo="qscaled/QPal" showThumbnail=true >}}
