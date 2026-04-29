# UAP4MA: Leveraging Multi-Agent Bandits to Generate Universal Adversarial Perturbations for Malware Attribution
## 📝Description
In this paper, we propose UAP4MA, a decision-based, problem-space, black-box method tailored for generating Universal Adversarial Perturbations (UAPs) toward APT malware attribution models. UAP4MA leverages a multi-agent Multi-Armed Bandit (MAB) framework to collaboratively construct UAPs via 13 functionality-preserving transformations, and integrates Optimized Initialization, Collaborative Multi-Agents, and Dynamic Agent Strategies to boost attack effectiveness, exploration efficiency, and convergence speed.
## 😊 Citation
If you find this paper or this repo is useful for you, please cite our paper on **IEEE TDSC**:

IEEE Reference Format:

**TODO**


#### Abstract
Advanced Persistent Threat (APT) malware group attribution is crucial for cybersecurity, yet current models remain vulnerable to adversarial attacks. Recent approaches for generating universal adversarial perturbations (UAPs) in the malware problem space have exposed substantial security risks, as a single UAP can mislead classification models across a wide range of malware. However, these methods are limited by suboptimal attack effectiveness and efficiency and rely heavily on confidence scores, restricting their practicality. To address these limitations, we propose **UAP4MA**, the first decision-based, problem-space, black-box UAP generation method tailored specifically for APT malware attribution models. UAP4MA employs a multi-agent Multi-Armed Bandit (MAB) framework, where agents collaboratively construct a UAP by applying functionality-preserving transformations chosen from 13 distinct types, leveraging Optimized Initialization, Collaborative Multi-Agents, and Dynamic Agent Strategies to enhance exploration and exploitation. Extensive experiments on our newly released **AMG43 dataset** (publicly available at https://github.com/Yuxia-Sun/UAP4MA/tree/main/AMG43) and the APTMalware dataset demonstrate UAP4MA’s outstanding attack performance, achieving over four times the fooling rate (FR), double the attack success rate (ASR), and an 80% reduction in training time compared to state-of-the-art methods. These results underscore UAP4MA’s effectiveness and efficiency, establishing it as a powerful and practical approach for challenging APT attribution models.
