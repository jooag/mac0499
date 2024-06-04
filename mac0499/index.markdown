---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: MAC0499
---


# Introduction

This is the page of the undergraduate thesis of **Antonio Fernando Silva e Cruz Filho** e **João Gabriel Andrade de Araujo Josephik**, advised by Professor **Nina Hirata**.

The goal of the project is to study, explore and compare different explainability methods for Convolutional Neural Networks.

# Proposal

Modern neural networks are very complex, formed by billions of parameters spread on multiple layers. Therefore, those system are often seen as "black box" systems: it's possible to visualize the input and output, but not the internal mechanisms of the network.

In this context, multiple methods were developed over the years to shed a light in the "reasoning" behind the system decisions. We aim to study methods developed specifically for Convolutional Networks.

Throughout the course of this research project, several important topics were (or will be) be studied. These topics may include:

- Feature Visualization models, such as [DeepDream](#deepdream)
- Pixel atribution models, implementing [GradCam](#gradcam)
- Using interpretable models (Like [KANs](#kan)) to create explanations about Neural Networks, using techniques like [LIME](#lime) and [SHAP](#shap).

Using the tools studied by this research, this project aims to contribute to existing knowledge about explainability and to possibily create new tools and techniques for explaining deep learning models.

# References

- <a id="deepdream"></a> Yosinski, J., Clune, J., Nguyen, A., Fuchs, T., & Lipson, H. (2015). Understanding Neural Networks Through Deep Visualization. ArXiv. /abs/1506.06579

- <a id="gradcam"></a> Selvaraju, R. R., Cogswell, M., Das, A., Vedantam, R., Parikh, D., & Batra, D. (2016). Grad-CAM: Visual Explanations from Deep Networks via Gradient-based Localization. ArXiv. https://doi.org/10.1007/s11263-019-01228-7

- <a id="lime"></a> Ribeiro, M. T., Singh, S., & Guestrin, C. (2016). "Why Should I Trust You?": Explaining the Predictions of Any Classifier. ArXiv. /abs/1602.04938

- <a id="shap"></a> Lundberg, S., & Lee, S. (2017). A Unified Approach to Interpreting Model Predictions. ArXiv. /abs/1705.07874

- <a id="kan"></a> Liu, Z., Wang, Y., Vaidya, S., Ruehle, F., Halverson, J., Soljačić, M., Hou, T. Y., & Tegmark, M. (2024). KAN: Kolmogorov-Arnold Networks. ArXiv. /abs/2404.19756

- <a id="book"></a> [*Interpretable Machine Learning: A Guide for Making Black Box Models Explainable*](https://christophm.github.io/interpretable-ml-book/)