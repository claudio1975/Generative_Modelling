# Harnessing Generative Models for Synthetic Non-Life Insurance Premium Data

This study is oriented to a synthetic non-life insurance premium dataset generated using several Conditional Generative Models. Unlike unconditional models, which create data freely without guidance, conditional models are directed by input conditions to produce targeted outputs. As a benchmark, has been employed a Conditional Gaussian Mixture Model. The validation of generated data followed several steps: data visualization comparison with univariate analysis, PCA and UMAP representations between trained data and samples generated. To evaluate the goodness of data generated has been employed in addition to these visual methods, consistecy check of data produced, the statistical Kolmogorov–Smirnov test and predictive modelling of frequency and severity with Generalized Linear Models (GLMs) exploited by Tweedie distribution as a measure of the generated data's quality followed by the evidence of features importance. For further comparison, advanced Deep Learning architectures have been employed: Conditional Variational Autoencoders (CVAEs), CVAEs enhanced with a Transformer Decoder, and a Conditional Diffusion Model. The analysis assesses each model’s ability to capture the underlying distributions, preserve complex dependencies, and maintain conditional relationships intrinsic to the premium data. These findings provide insightful directions for enhancing synthetic data generation in insurance, with potential applications in risk modelling, pricing strategies with data scarcity, and regulatory compliance.

Keywords: 

Conditional Variational Autoencoders, Conditional Gaussian Mixture Model, Conditional Diffusion Model, Conditional Variational Autoencoders with a Transformer Decoder, PCA, UMAP, GLMs

References: 

1. Ian Goodfellow and Yoshua Bengio and Aaron Courville, 2016, *Deep Learning*, MIT Press.
2. Mario V. Wuthrich, Ronald Richman, Benjamin Avanzi, Mathias Lindholm, Michael Mayer, Jürg Schelldorfer, Salvatore Scognamiglio, 2025, *AI Tools for Actuaries*, SSRN.
3. David Foster, 2023, *Generative Deep Learning, 2nd Edition*, O'Reilly.
4. Jake VanderPlas, 2016, *Python Data Science Handbook*, O'Reilly.
5. Jamotton, Charlotte ; Hainaut, Donatien, 2023, *Variational autoencoder for synthetic insurance data*, ISBA.

