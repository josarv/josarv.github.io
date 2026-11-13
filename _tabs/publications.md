---
title: Publications
icon: fas fa-book
order: 1
---

[Google Scholar](https://scholar.google.com/citations?user=kykvvqEAAAAJ&hl=en) ·
[DBLP](https://dblp.org/pid/317/1641.html) ·
[ORCID](https://orcid.org/0009-0002-9548-7757)

### Leveraging Apache Spark for Appliance-Level Load Monitoring with Ensemble Learning Techniques

**Iosif (Joseph) Arvanitis**, Menelaos Panagiotis Papastergiou, Agorakis Bompotas, Evangelos Geraridis, Ioanna Giannoukou, Ioannis Karydis, Spyros Sioutas

*ALGOCLOUD 2024*, LNCS vol. 15455, Springer, pp. 107–116

[DOI](https://doi.org/10.1007/978-3-031-94677-6_8) ·
[PDF](https://cir.di.ionio.gr/karydis/my_papers/APMGGKarydisS2024%20-%20Leveraging%20Apache%20Spark%20for%20Appliance-Level%20Load%20Monitoring%20with%20Ensemble%20Learning%20Techniques.pdf)

<details markdown="1">
<summary>Abstract</summary>

Appliance load monitoring measures the electricity consumption of household appliances, driven by motivations such as financial savings, reducing environmental impact, and predictive maintenance. It provides users with detailed energy usage information, leading to informed decisions about appliance operation and replacement, significant savings, and reduced carbon footprints. Traditionally relying on individual smart meters, a costly and complex method, load monitoring has evolved with non-intrusive load monitoring (NILM), which estimates individual appliance power use by analyzing overall household consumption. This shift, coupled with the exponential data growth from widespread smart meter adoption, necessitates scalable processing techniques. Apache Spark, a distributed processing framework, offers a solution with its scalability and flexibility, handling expanding workloads effectively. However, due to Spark's lack of built-in support for deep learning and specialized NILM algorithms, in this paper, we explore whether simpler solutions like Random Forests and Gradient-Boosted trees within Spark's MLlib are able to produce satisfactory results. Our experimental evaluation demonstrated that these algorithms perform well, especially for devices with smoother consumption patterns, highlighting the potential of shallow machine learning techniques in NILM applications, making them practical for real metering systems where data volume and speed rule out more complex solutions.

</details>

### A Systematic Analysis of the event-stream Incident

**Iosif (Joseph) Arvanitis**, Grigoris Ntousakis, Sotiris Ioannidis, Nikos Vasilakis

*EuroSec 2022* (15th European Workshop on Systems Security, co-located with EuroSys), ACM, pp. 22–28

[DOI](https://doi.org/10.1145/3517208.3523753) ·
[PDF](https://dl.acm.org/doi/pdf/10.1145/3517208.3523753)

<details markdown="1">
<summary>Abstract</summary>

On October 5, 2018, a GitHub user announced a critical security vulnerability in event-stream, a JavaScript package meant to simplify working with data-streams. The vulnerability was introduced by a new maintainer, by including code designed to harvest account details from select Bitcoin wallets when executing as part of the Copay wallet. At the time of the incident, event-stream was used by hundreds of applications and averaged about two million downloads per week. This paper reports on the results of an independent analysis of the event-stream incident. A series of steps allowed the attacker to take control of important account functions, while the attack was designed to activate only on select few environments---only when part of a specific dependency tree, only on specific wallets, and only on the live Bitcoin network. Conventional program analysis techniques would have likely missed the attack, and manual vetting proved to be inadequate given the scale and complexity of dependencies typical of modern applications. The event-stream incident provides an important case study of the risks associated with long and convoluted chains of third-party components, calling the research community to arms.

</details>
