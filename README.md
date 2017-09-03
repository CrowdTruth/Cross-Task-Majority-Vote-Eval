# CrowdTruth Evaluation Dataset

Corpus of crowdsourced annotations together with trusted judgments for 4 crowdsourcing tasks:

1. *medical relation extraction*
2. *Twitter event extraction*
3. *news event identification*
4. *sound interpretation*

The dataset was used to evaluate the [CrowdTruth](http://crowdtruth.org/) crowdsourcing aggregation metrics. Details are available in the paper:

* Anca Dumitrache, Oana Inel, Benjamin Timmermans, Carlos Ortiz, Robert-Jan Sips and Lora Aroyo: **[Empirical Methodology for Crowdsourcing Ground Truth](http://www.semantic-web-journal.net/system/files/swj1569.pdf)**. [Semantic Web Journal 2017](http://www.semantic-web-journal.net/) (in review).

For each of the 4 tasks, 2 files are given:

* ```*_raw.csv``` - Contains the judgments of individual workers for each of the tasks.

* ```*_aggregated.csv``` - Contains the CrowdTruth aggregation of the judgments for each unit in the task expressed as the *media unit - annotation score*, as well as the trusted judgment. 