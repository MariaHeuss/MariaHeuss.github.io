---
layout: page
title: Publications
permalink: /publications
show_title: true
published: true
---

## RankingSHAP – Listwise Feature Attribution Explanations for Ranking Models 
__Maria Heuss, Maarten de Rijke, Avishek Anand__. Preprint 
[pdf](/assets/rankingshap.pdf), [bibtex](/assets/bibtex/rankingshap.txt), [code](https://github.com/MariaHeuss/RankingShap)

Explaining ranking decisions, which aggregate numerous small judgments about the relative order of documents, present a unique challenge. It's essential to pinpoint the exact decision we aim to explain. In this paper, we introduce a concept of feature attribution for ranking models, concentrating on one aspect of the ranking decision at a time, such as the overall ranking order or the rationale behind placing a particular document at the top of the list. We develope a framework that, upon identifying the specific aspect for explanation, enables the use of the renowned explainability tool, SHAP, to produce feature attribution explanations.


## Predictive Uncertainty-based Bias Mitigation in Ranking 
__Maria Heuss, Daniel Cohen, Masoud Mansoury, Maarten de Rijke, and Carsten Eickhoff__. Published in CIKM 2023: 32nd ACM International Conference on Information and Knowledge Management  [pdf](/assets/pufr.pdf), [bibtex](/assets/bibtex/pufr.txt), [code](https://github.com/MariaHeuss/2023-CIKM-uncertainty-based-bias-mitigation)

Since model decisions, in this case ranking score predictions, usually can only be made with a degree of uncertainty, in this work we propose to make use of that uncertainty to strategically trade of the utility with the fairness of a ranking model where the model is most uncertain about the ordering of the documents. Our approach, called **P**redictive **U**ncertainty-based **F**air **R**anking or short __PUFR__ allows documents to swap place within a certain confidence interval. We show empirically that this allows us to effectively improve the fairness of the model with minimal decrease of utility.  

## Fairness of Exposure in Light of Incomplete Exposure Estimation 
__Maria Heuss, Fatemeh Sarvi, and Maarten de Rijke__. Published in SIGIR 2022: 45th international ACM SIGIR Conference on Research and Development in Information Retrieval [pdf](/assets/felix.pdf), [bibtex](/assets/bibtex/felix.txt), [code](https://github.com/MariaHeuss/2022-SIGIR-FOE-Incomplete-Exposure)

As recent work has shown (see our following paper), while for most ranked lists the commonly assumed position-based exposure distribution holds, for some ranked lists that contain for example visual outliers, the exposure distribution differs. 
In this paper we tackle the problem of ensuring the fairness of a ranking model when for some ranked lists we do not know the exposure distribution. 

## Understanding and Mitigating the Effect of Outliers in Fair Ranking 
__Fatemeh Sarvi, Maria Heuss, Mohammad Aliannejadi, Sebastian Schelter, and Maarten de Rijke__. Published in WSDM 2022: The Fifteenth International Conference on Web Search and Data Mining [pdf](/assets/omit.pdf), [bibtex](/assets/bibtex/omit.txt)

In this work we investigate the role of visual outliers on the exposure distribution in ranked lists. We formalize outlierness in a ranking, show that outliers are present in realistic datasets, and present the results of an eye-tracking study, showing that users’ scanning order and the exposure of items are influenced by the presence of outliers and propose a simple but effective approach to decrease the number of outliers on top of the ranked list. 