
# Lifelong Variational Autoencoder via Online Adversarial Expansion Strategy

>📋 This is the implementation of Lifelong Variational Autoencoder via Online Adversarial Expansion Strategy

>📋 Accepted by AAAI 2023 (Oral)

# Title : Lifelong Variational Autoencoder via Online Adversarial Expansion Strategy

# Paper link : https://www.researchgate.net/profile/Adrian-Bors/publication/365926924_Lifelong_Variational_Autoencoder_via_Online_Adversarial_Expansion_Strategy/links/63893987ca2e4b239c7aac41/Lifelong-Variational-Autoencoder-via-Online-Adversarial-Expansion-Strategy.pdf


# Abstract
The Variational Autoencoder (VAE) suffers from a significant loss of information when trained on a non-stationary data distribution. This loss is called catastrophic forgetting, which has been less studied theoretically in VAEs. In this paper, we analyse the forgetting behaviour of VAE in continual generative modelling by developing a new lower bound on the data likelihood, which interprets the forgetting process as an increase in the probability distance between the generator distribution and the evolved data distribution. The proposed bound shows that a VAE-based dynamic expansion model can achieve better performance if its capacity increases appropriately considering the shift in the data distribution. Based on this analysis, we propose a novel expansion criterion that aims to preserve the information diversity among VAE components, while ensuring that acquires more knowledge with fewer parameters. Specifically, we implement this expansion criterion from the perspective of a multi-player game and propose the Online Adversarial Expansion Strategy (OAES), which considers all previously learned components as well as the currently updated component as multiple players while an adversary model evaluates their performance. The proposed OAES can dynamically estimate the discrepancy between each player and the adversary without accessing task information. This leads to the gradual addition of new components while ensuring the knowledge diversity among all of them. We show theoretically and empirically that the proposed extension strategy can enable a VAE model to achieve the best performance given an appropriate model size.

# Environment

1. Tensorflow 2.1
2. Python 3.6

# Training and evaluation

>📋 Python xxx.py, the model will be automatically trained and then report the results after the training.

>📋 Different parameter settings of OCM would lead different results and we also provide different settings used in our experiments.

# BibTex
>📋 If you use our code, please cite our paper as:


