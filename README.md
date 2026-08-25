# Securing SDN Networks from BotNet Threats: A Machine Learning-Based Defense Strategy

## Overview
This repository contains the implementation and experimental results of the research paper titled "Securing SDN Networks from BotNet Threats: A Machine Learning-Based Defense Strategy" by Muhammad Hassan Mukhtar. The paper presents an advanced defense strategy designed to secure SDN networks against BotNet threats using machine learning techniques.

## Read the Paper
- **Markdown:** [Securing SDN Networks from BotNet Threats: A Machine Learning-Based Defense Strategy](Paper/Securing%20SDN%20Networks%20from%20BotNet%20Threats%20A%20Machine%20Learning%20Based%20Defense%20Strategy.md)
- **Original PDF:** [Securing SDN Networks from BotNet Threats A Machine Learning Based Defense Strategy.pdf](Paper/Securing%20SDN%20Networks%20from%20BotNet%20Threats%20A%20Machine%20Learning%20Based%20Defense%20Strategy.pdf)

## Article Information
- **Author**: Muhammad Hassan Mukhtar
- **Affiliation**: Air University Islamabad, Pakistan
- **Written on**: 31st December 2023
- **GitHub Release Date**: 31st December 2023
- **Available Online**: 1st January 2024

## Keywords
- SDN
- Security
- Attacks
- BotNet
- DoS
- DDoS
- Research challenges
- Survey

## Abstract
With the increasing prevalence of Software-Defined Networking (SDN), there is a growing susceptibility of networks to malicious entities, particularly BotNets. This paper presents an advanced defense strategy designed to secure SDN networks against BotNet threats. Harnessing the capabilities of machine learning, our innovative approach prioritizes the proactive identification and mitigation of potential risks. By integrating intelligent algorithms, our proposed solution strengthens the network's ability to discern between normal and malicious activities, effectively thwarting BotNet recruitment attempts. The amalgamation of SDN and machine learning not only reinforces the network infrastructure but also establishes a dynamic and adaptive defense mechanism capable of evolving with emerging threats. The experimental results underscore the efficacy of our approach in significantly reducing the risk of BotNet attacks, providing a robust and resilient security framework for SDN environments. In the context of Denial of Service (DoS) and Distributed Denial of Service (DDoS) attacks, where a multitude of machines are recruited for coordinated attacks to block traffic to a specific site, our solution offers a protective measure to prevent small devices from becoming unwitting participants in such botnets.


## Repository Structure
- [Paper/](Paper/Securing%20SDN%20Networks%20from%20BotNet%20Threats%20A%20Machine%20Learning%20Based%20Defense%20Strategy.md) — the paper in Markdown ([figures](Paper/images/)) and the original PDF
- [Code/](Code/Securing%20SDN%20Networks%20from%20BotNet%20Threats%20A%20Machine%20Learning%20Based%20Defense%20Strategy.ipynb) — Jupyter notebook with the preprocessing, training and evaluation pipeline
- [Data/](Data/data.csv) — `data.csv`, 125,972 labelled network-traffic samples across 43 columns

## Results
| Model | Training | Test | Validation |
|---|---|---|---|
| SVM (LinearSVC) | 94.48% | 94.33% | 94.40% |
| Decision Tree (depth 3) | 95.51% | 95.50% | 95.44% |
| Decision Tree (no max depth) | 99.93% | 99.44% | 99.48% |
| Random Forest | 99.93% | 99.57% | 99.60% |

XGBoost Regression MSE — Training: 1.1678 · Test: 1.3131 · Validation: 1.2575
