---
guid: "news-10407"
pubDate: "Fri, 25 Jun 2021 11:42:57 +0200"
title: "Paper Accepted for ACM DTRAP Journal"
link: "https://sse.cs.tu-dortmund.de/newsdetail/paper-accepted-for-dtrap21-journal-10407/"
enclosure: ""
source: "Paper Accepted for ACM DTRAP Journal"
summary: "In our paper, we present an in-depth analysis on how and when library maintainers react to the disclosure and publication of vulnerabilities, and how long it takes to release appropriate patches."
---
Our paper "Analyzing the Direct and Transitive Impact of Vulnerabilities onto Different Artifact Repositories" will be part of ACM DTRAP's special issue on vulnerabilities

In our paper, we present an in-depth analysis on how and when library maintainers react to the disclosure and publication of vulnerabilities, and how long it takes to release appropriate patches. We especially focus on vulnerabilities contained in transitive dependencies, as those are often hard to identify both for maintainers and software developers.

In order to do so, we present a tool that accumulates the artifact dependency graphs for entire artifact repositories, and execute it for *Maven Central*, the *NPM Registry* and *NuGet.org*. We further annotate those dependency graphs with verified information on vulnerabilities (provided by [*Snyk Ltd.*](https://snyk.io/)), enabling us to analyze the direct and transitive influence that vulnerabilities may have. Our final data set contains information on a total of 21.8 million software artifacts spread across 1.9 million libraries, and incorporates 7110 vulnerabilities.

The [ACM Digital Threats: Research and Practice (DTRAP)](https://dl.acm.org/journal/dtrap) journal started in 2020 and aims to bridge the existing gap between academic research and industry pratice. Our paper will be published in a special journal issue on vulnerabilities.

[Preprint](/storages/sse-cs/r/Publications/Preprints/vuln_impact_analysis.pdf)

![Paper Accepted for ACM DTRAP Journal](/images/news-10407_2.PNG)
