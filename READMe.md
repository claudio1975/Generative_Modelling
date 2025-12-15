# Harnessing Generative Models for Synthetic Non-Life Insurance Data

![matplotlib](https://img.shields.io/badge/matplotlib-3.10.0-green)
![seaborn](https://img.shields.io/badge/seaborn-0.13.2-yellow)
![numpy](https://img.shields.io/badge/numpy-2.0.2-blue)
![pandas](https://img.shields.io/badge/pandas-2.2.2-red)
![scikit-learn](https://img.shields.io/badge/scikitlearn-1.6.1-orange)
![tensorflow](https://img.shields.io/badge/tensorflow-2.19.0-brown)
![shap](https://img.shields.io/badge/shap-0.50.0-purple)
![umap](https://img.shields.io/badge/umap-0.5.9-yellow)

Obtaining realistic and publicly accessible datasets is a major barrier to advancing actuarial research and developing open-source tools for 
insurance analytics. This study is oriented to a synthetic non-life insurance premium dataset generated using various Generative Models.

A Conditional Gaussian Mixture Model (CGMM) has been employed as a benchmark. The methodology involved splitting the dataset into two subsets 
based on the "claim occurence" column. For each subset, a multivariate Gaussian Mixture Model is fitted allowing to model complex, 
multi-modal distributions. 
This benchmark was then compared with advanced Deep Learning architectures, including a Conditional Variational Autoencoder (CVAE), a Conditional 
Variational Autoencoder with a Transformer-based Decoder (CTVAE), and a Conditional Diffusion Model (CDM). Additionally, the GPT-5.1 Large Language Model 
was used to generate synthetic datasets through prompt instructions.

The experiments were conducted on two insurance datasets retrieved from the CASdatasets R package. In the first experiment, a portion of each complete 
dataset was fed into the generative models, which were asked to generate an equal length of records. In the second experiment, a smaller portion of 
each dataset was used, with the models asked to produce a larger number of rows, equal of the first experiment. In the final trial, the gender variable 
was omitted to enhance privacy.

Validation of the generated data included several steps: data visualization with comparison through univariate analysis, PCA and UMAP representations, 
evaluation the consistency of the produced data with the original, and the statistical Kolmogorov-Smirnov test. Predictive modeling of frequency and 
severity using Generalized Linear Models (GLMs) based on Tweedie distribution were employed as metrics for assessing the quality of the generated data. 
Furthermore, the importance of features was analyzed.

This analysis evaluates each model’s ability to accurately capture underlying distributions, preserve complex dependencies, and maintain intrinsic relationships. 
The findings offer valuable insights for improving synthetic data generation in the insurance field, potentially enhancing risk modeling, pricing strategies 
in the face of data scarcity, and ensuring regulatory compliance.

Keywords: 

Conditional Variational Autoencoder, Conditional Gaussian Mixture Model, Conditional Diffusion Model, Conditional Variational Autoencoder with a Transformer-based Decoder, 
GPT-5.1 Large Language Model, PCA, UMAP, GLMs

References: 

1. Ian Goodfellow and Yoshua Bengio and Aaron Courville, 2016, *Deep Learning*, MIT Press.
2. Mario V. Wuthrich, Ronald Richman, Benjamin Avanzi, Mathias Lindholm, Michael Mayer, Jürg Schelldorfer, Salvatore Scognamiglio, 2025, *AI Tools for Actuaries*, SSRN.
3. David Foster, 2023, *Generative Deep Learning, 2nd Edition*, O'Reilly.
4. Jake VanderPlas, 2016, *Python Data Science Handbook*, O'Reilly.
5. Jamotton, Charlotte ; Hainaut, Donatien, 2023, *Variational autoencoder for synthetic insurance data*, ISBA.
6. Harshvardhan GM, Mahendra Kumar Gourisaria, Manjusha Pandey, Siddharth Swarup Rautaray, 2020, *A comprehensive survey and analysis of generative models in machine learning*, ScienceDirect.

You can read the [article](https://medium.com/@c.giancaterino/stop-waiting-for-data-how-generative-models-are-reshaping-insurance-analytics-ec102a2e5177)
You can watch results from the [demo app](https://huggingface.co/spaces/towardsinnovationlab/Generative_Models_4_Insurance_Data)

