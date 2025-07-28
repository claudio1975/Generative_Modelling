# Harnessing Generative Models for Synthetic Non-Life Insurance Data

This study is oriented to a synthetic non-life insurance premium dataset generated using several Generative Models. As a benchmark, a Conditional Gaussian Mixture Model has been employed. The validation of the generated data involved several steps: data visualisation, comparison with univariate analysis, PCA and UMAP representations between the trained data and the generated samples. In addition, check the consistency of data produced, the statistical Kolmogorov–Smirnov test and predictive modelling of frequency and severity with Generalised Linear Models (GLMs) exploited by Tweedie distribution as a measure of the generated data's quality, followed by the evidence of features importance. For further comparison, advanced Deep Learning architectures have been employed: Conditional Variational Autoencoders (CVAEs), CVAEs enhanced with a Transformer Decoder, a Conditional Diffusion Model, and Large Language Models. The analysis assesses each model’s ability to capture the underlying distributions, preserve complex dependencies, and maintain relationships intrinsic to the premium data. These findings provide insightful directions for enhancing synthetic data generation in insurance, with potential applications in risk modelling, pricing strategies with data scarcity, and regulatory compliance.

Keywords: 

Conditional Variational Autoencoders, Conditional Gaussian Mixture Model, Conditional Diffusion Model, Conditional Variational Autoencoders with a Transformer Decoder, Large Language Models, PCA, UMAP, GLMs

References: 

1. Ian Goodfellow and Yoshua Bengio and Aaron Courville, 2016, *Deep Learning*, MIT Press.
2. Mario V. Wuthrich, Ronald Richman, Benjamin Avanzi, Mathias Lindholm, Michael Mayer, Jürg Schelldorfer, Salvatore Scognamiglio, 2025, *AI Tools for Actuaries*, SSRN.
3. David Foster, 2023, *Generative Deep Learning, 2nd Edition*, O'Reilly.
4. Jake VanderPlas, 2016, *Python Data Science Handbook*, O'Reilly.
5. Jamotton, Charlotte ; Hainaut, Donatien, 2023, *Variational autoencoder for synthetic insurance data*, ISBA.
6. Harshvardhan GM, Mahendra Kumar Gourisaria, Manjusha Pandey, Siddharth Swarup Rautaray, 2020, *A comprehensive survey and analysis of generative models in machine learning*, ScienceDirect.

