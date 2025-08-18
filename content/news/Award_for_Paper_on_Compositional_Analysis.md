---
guid: "news-10257"
pubDate: "Tue, 22 Jun 2021 08:16:56 +0200"
title: "Award for Paper on Compositional Analysis"
link: "https://sse.cs.tu-dortmund.de/newsdetail/award-for-paper-on-compositional-analysis-10257/"
enclosure: ""
source: "Award for Paper on Compositional Analysis"
summary: "In static program analysis, whole-program analysis (WPA) describes the process of analyzing a complete program including all of its dependencies and system libraries."
---
Our Paper "Lossless, Persisted Summarization of Static Callgraph, Points-To and Data-Flow Analysis" receives the ECOOP'21 Distinguished Paper Award. With the approach presented here we can modularize static program analyses based of PhASAR and can save on average 72% of analysis time in whole-program analysis.

In static program analysis, whole-program analysis (WPA) describes the process of analyzing a complete program including all of its dependencies and system libraries. The goal here is to derive properties of the program (e.g. security guarantees or counterexamples) with high precision including (almost) everything included in the subsequent execution of the program. However, this process can be very costly as the amount of library and system code required to analyze usually exceeds the amount of application code.

Interestingly, this rather large part of the application stack rarely changes between analysis runs. In our recent ECOOP Paper, we leverage that fact and provide a lossless modular summarization technique that blends into analyses with PhASAR.

For this paper, we have just been awarded the **Distinguished Paper Award** at ECOOP'21. Only two papers of the conference were presented with this award this year. We are very happy and grateful to be selected.

**Paper Preprint:** [Lossless, Persisted Summarization of Static Callgraph, Points-To and Data-Flow Analysis](/storages/sse-cs/r/Publications/Preprints/shb-mwa-ecoop21.pdf)

![Award for Paper on Compositional Analysis](/images/news-10257_2.png)
