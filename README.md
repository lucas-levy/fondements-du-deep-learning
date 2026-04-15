# Deep Learning Theory

Labs from the Master MVA **[Deep Learning Theoretical Foundations](https://www.master-mva.com/cours/fondements-theoriques-du-deep-learning/)** class. This graduate course covers recent research results on Deep Learning mathematical theory: **Optimization in NNs Loss Landscape**, **Generalization of NNs**, and **Robustness in DL**, among others.
This repository contains the three labs of the lass part of the class, taught by Nicolas Thome and Gianni Franchi, and dedicated to Robustness.

## TP1 and 2. Bayesian Linear Regression and Approximate Inference

The first two labs are focused on understanding **Bayesian Models**, that allow to integrate uncertainty quantification into models.
The first lab is focused on Bayesian Linear Regression, mostly in the one-dimensional setting. 
The second lab is about Approximate Inference methods for classification. 
We explore Laplacian approximation, Variational Inference, and Bayesian Neural Networks on two-dimensional toy datasets.

<p align="center">
<img height="250" alt="visu_tp2_1" src="https://github.com/user-attachments/assets/38634a8b-23f2-4694-b16b-d7f41951e5a5" />
<img height="250" alt="visu_tp2_2" src="https://github.com/user-attachments/assets/e3079671-9026-4e3f-9815-f4be2a03bbb9" />
</p>

## TP3. Out-of-Distribution Detection and Neural Collapse

This lab is focused on two recent topics in Deep Learning research: **Out-of-Distribution Detection (OOD)**, and **Neural Collapse**. 
OOD focuses on recognizing when a model is given inputs that do not follow the distribution of its training data, so that such cases can be flagged or handled separately. 
We aim at reproducing the results of "OpenOOD v1.5: Enhanced Benchmark for Out-of-Distribution Detection" (Zhang et. al., 2024), by evaluting several OOD methods.

<p align="center"><img height="300" alt="visu_tp3_1" src="https://github.com/user-attachments/assets/a401df44-6af8-4097-a2fa-988e67ecc8c0" /></p>

In the second part, we study Neural Collapse, a phenomenon appearing during the terminal phase of training, where the network organizes its representations so that examples of the same class become nearly identical, while different classes are evenly and maximally spread apart.
We reproduce the results of "Prevalence of Neural Collapse during the terminal phase of deep learning training" (Papyan et. al., 2020), who first observed this phenomenon, and proposed a series of indicators to observe it.




