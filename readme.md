# Artifacts
This repository contain the artifacts for the paper: *Demystifying Harmful Content in Ethereum Transactions*.

**Warning⚠️:** This repository contain *OFFENSIVE* and *EXPLICIT* content, please use it responsibly.

Specifically, this repository includes **anonymized dataset**, **potentially harmful content**, and **harmful content classification criteria**.

- [`./dataset/`](dataset): The dataset containing 9,148 text segments, 9,528 URLs and 9,931 files extracted from Ethereum transactions. Note that all the data in this dataset has been anonymized and sanitized to remove personal information and prevent security issues. 

- [`./harmful-content/`](harmful-content): We identified 638 distinct potentially harmful cases in the dataset, categorized them, and anonymized the data.

- [`./criteria/readme.md`](criteria/readme.md): The detailed criteria for harmful content classification and example cases.


## Introduction
Users can store arbitrary content on Ethereum through transactions, however, this freedom introduces the risk of embedding harmful content on blockchain. Due to the immutability and transparency of blockchain, once harmful content is recorded, it cannot be removed and is accessible to everyone, which could cause widespread and lasting negative impacts on the real world. 
 
## Findings
We extracted 96,687 text segments, 9,931 files, and 1,198,889 URLs from 2,224,215,240 Ethereum transactions. Through sampling and the open card sorting approach, we randomly sampled 9,148 text segments and 9,528 URLs for examination, and reviewed all 9,931 files, providing a 95% confidence level and a 1% confidence interval.

We identified 638 cases of potentially harmful content, accounting for **3.2%** of all sampled content. These cases is classified into six categories: **Privacy Violation**, **Sexual Content**, **Discrimination**, **On-chain Crime**, **Personal Threat**, and **Child Maltreatment**.

The data collected in this study should be anonymized for ethical considerations. However, anonymizing the entire dataset would be too labor-intensive, so we anonymized the sampled data and used it as the anonymized dataset.
**We anonymized and open-sourced the sampled dataset, as well as potentially harmful cases and classification criteria.**

