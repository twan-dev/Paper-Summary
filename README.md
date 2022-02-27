# SCRF: Template - Research Summary

---
title: [Research Summary - DO NOT RUG ON ME: ZERO-DIMENSIONAL SCAM DETECTION]
description: One or two sentences of what the post is about.
tags: [DeFi, Machine learning, Scam Detection,Rug pulls]
created: [2020-12-25]
researcher: [Bruno Mazorra and Victor Adan]
---

> ### TLDR
>
> - The reaserchers expand the dataset of Uniswap v2 scam tokens.
> - They provide  a theoretical classification of three different types of rug pulls and provide tools to identify them.
> - The authors introduce two highly accurate and precise Machine learning-based models to discriminate between malicious and nonmalicious tokens in different scenarios before the malicious manuever.

### Core Research Question

Do rug pulls in Constant Function Marker Makers (CFMM) share similar features? Can we predict if a project is a rug pull before the malicius manuver? 

### Citation

- Mazorra, Bruno, Victor Adan, and Vanesa Daza. "Do not rug on me: Zero-dimensional Scam Detection." arXiv preprint arXiv:2201.07220 (2022).

### Background

-

### Summary

1. Introduction.
2. Related Work.
3. Preliminars
    - Backround.
4. Malicious Uniswap Maneuvers
    - Classification of different type of rug pulls.
5. Data Collection:
    - Overview of the method used to extract all the necessary data.
6. Token Labelling.
    - Provide the methodology to label tokens as scams or non-scams.
    - Overview of the results obtained by the labelling methodology proposed.
7. 


### Method

We defined two methods that use Machine Learning models to discriminate between malicious and non-malicious tokens in different scenarios. In the first scenario, tokens can be evaluated at any block prior to the malicious maneuver. In the second scenario, all tokens are evaluated at a certain time after the creation of their respective pools. Specifically, we use a new Machine Learning algorithm based on attention mechanisms for tabular data called FT-Transformer.

Describe the general approach of the paper (e.g scientific experiment, data/modeling, mathematical proofs) then outline the key steps that the researchers undertook to perform the study.

For each key step, summarize the nature of the specific approach that the researchers used to complete each step (e.g. statistical test, logic proof, data-driven model).

### Results

###### Activity based Method Results

<img src="Results1 method.png" width="50%" />

### Discussion and Key Takeaways

Summarize any discussion/commentary sections included by the researchers. Identify the most concise description of any perspectives or viewpoints the researchers explored in this section.

Summarize the conclusions or key takeaways as included by the researchers.

### Implications and Follow-ups

Summarize the implicit or explicit implications of the study. If the researchers include such a section, include a few of the most important points discussed. If not, insert some commentary of clear-cut or obvious implications of the work.

Share any follow-up work discussed by the researchers.

### Applicability

- To better understand the methodology used by scammers to execute rug pulls.
- Provide machine learning tools to protect users from permanet losses. 
