---
guid: "news-33995"
pubDate: "Mon, 07 Aug 2023 15:32:11 +0200"
title: "Paper on Modular Static Analyses Published at ASE '23"
link: "https://sse.cs.tu-dortmund.de/newsdetail/paper-on-modular-static-analyses-published-at-ase-23-33995/"
enclosure: ""
source: "Paper on Modular Static Analyses Published at ASE '23"
summary: "Our research paper Persisting and Reusing Results of Static Program Analyses on a Large Scale was accepted at ASE 2023 in Luxembourg."
featured_image: "/featured.png"
---
![Paper on Modular Static Analyses Published at ASE '23](/featured.png)

We propose a novel approach for publishing, linking, and re-using (partial) results of static program analyses and find that it improves the performance of existing analyses, while also providing benefits for other areas of application, including artifact evaluation.

Our research paper **Persisting and Reusing Results of Static Program Analyses on a Large Scale** was accepted at ASE 2023 in Luxembourg. In our work, we survey 40 state-of-the-art implementations of static program analyses (SPAs) regarding the format and semantics of their outputs. We find that while more and more analyses are built in a modular fashion - and would therefore benefit from using partial or precomputed results - in practice such results are rarely documented or even persisted. To tackle the problem, we propose *SPARRI,*a novel tool for publishing, reusing, and indexing results of SPAs in a unified, explainable result format. SPARRI provides built-in facilities to reference software artifacts located on Maven central but is extendable to support arbitrary ecosystems and repositories. Our evaluation of SPARRI shows that reusing partial results can reduce execution times for tasks like whole-program call graph construction by up to 92%. Furthermore, we see potential in applying it to other research areas like empirical software studies, benchmark creation, and artifact evaluation.
