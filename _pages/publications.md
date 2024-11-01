---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

**As large as it gets – Studying Infinitely Large Convolutions via Neural Implicit Frequency Filters**  
**J. Grabinski**, J. Keuper, M. Keuper    
TMLR 2024 (Featured Certification) 
In this paper, we introduce a new tool, Neural Implicit Frequency Filters (NIFF), to study the effective filter size learned by CNNs. Our NIFF inherently solves the following challenges (1) we need an effective means to train models with large filters (potentially as large as the input data) without increasing the number of learnable parameters; (2) the employed convolution operation should be a plug-and-play module that can replace conventional convolutions in a CNN and allow for an efficient implementation in current frameworks; (3) the study of filter sizes has to be decoupled from other aspects such as the network width or the number of learnable parameters; (4) the cost of the convolution operation itself has to remain manageable i.e.~we can not naively increase the size of the convolution kernel.

[PDF](https://openreview.net/forum?id=xRy1YRcHWj) |  [Code](https://github.com/GeJulia/NIFF)


**Improving Feature Stability during Upsampling – Spectral Artifacts and the Importance of Spatial Context**     
S. Agnihotri, **J. Grabinski**, M. Keuper   
ECCV 2024  
In this paper, we analyse the importance of spatial context during upsampling in pixel-wise prediction tasks and find that the availability of large spatial context during upsampling allows to provide stable, high-quality pixel-wise predictions.

[PDF](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/07582.pdf)


**On the unreasonable vulnerability of transformers for image restoration-and an easy fix**     
S. Agnihotri, KV. Gandikota, **J. Grabinski**, P. Chandramouli, M. Keuper       
ICCV 2023, Workshop on Adversarial Robustness In the Real World     
In this paper, we indicate that modern ViT models for pixel-wise prediction tasks are highly susceptible to adversarial attacks which is contrary to image classification ViTs which are less susceptible to pixel-wise adversarial attacks. We attempt to improve their robustness through adversarial training. While this yields a significant increase in robustness for Restormer, results on other networks are less promising and relate this fact to the type of acitivation function used after downsampling.

[PDF](https://openaccess.thecvf.com/content/ICCV2023W/AROW/papers/Agnihotri_On_the_Unreasonable_Vulnerability_of_Transformers_for_Image_Restoration_-_ICCVW_2023_paper.pdf)


**Robust Models are less Over-Confident**  
**J. Grabinski**, P. Gavrikov, J. Keuper, M. Keuper    
NeurIPS 2022  
In this paper, we empirically analyze a variety of adversarially trained models that achieve high robust accuracies when facing state-of-the-art attacks and we show that adversarial training has an interesting side-effect: it leads to models that are significantly less overconfident with their decisions even on clean data than non-robust models. 

[PDF](https://openreview.net/forum?id=5K3uopkizS) |  [Code](https://github.com/GeJulia/robustness_confidences_evaluation)


**FrequencyLowCut Pooling--Plug & Play against Catastrophic Overfitting**  
**J. Grabinski**, S. Jung, J. Keuper, M. Keuper    
ECCV 2022  
In this paper, we develop a new kind of pooling layer which can be easily plugged into any CNN architecture: FrequencyLowCut pooling. Our experiments show, that in combination with simple and single-step adversarial training, our hyper-parameter free operator substantially improves model robustness and avoids catastrophic overfittingIn this paper, we develop a new kind of pooling layer which can be easily plugged into any CNN architecture: FrequencyLowCut pooling. Our experiments show, that in combination with simple and single-step adversarial training, our hyper-parameter free operator substantially improves model robustness and avoids catastrophic overfitting. 

[PDF](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136740036.pdf) |  [Code](https://github.com/GeJulia/flc_pooling)

**Aliasing and adversarial robust generalization of CNNs**  
**J. Grabinski**, J. Keuper, M. Keuper    
ECML 2022  
In this paper, we analyze single-step adversarial training which is prune to the phenomena of catastrophic overfitting and show that catastrophic overfitting is correlated with an increase in aliasing in the networks downsampling layer. Thus we develop a new early stopping criteria for single-step adversarial training based on our aliasing measurement.  

[PDF](https://link.springer.com/article/10.1007/s10994-022-06222-8) 

**Robust Models are less Over-Confident**  
**J. Grabinski**, P. Gavrikov, J. Keuper, M. Keuper    
ICML 2022, Workshop New Frontiers in Adversarial Machine Learning   
In this paper, we empirically analyze a hand full of adversarially trained models that achieve high robust accuracies when facing state-of-the-art attacks and show that adversarial training can lead to models that are significantly less overconfident with their decisions.  

[PDF](https://arxiv.org/pdf/2210.05938.pdf) 

**Aliasing coincides with CNNs vulnerability towards adversarial attacks**  
**J. Grabinski**, J. Keuper, M. Keuper    
AAAI 2022, Workshop on Adversarial Machine Learning and Beyond    
In this paper, we analyze adversarially trained, robust models in the context of a specifically suspicious network operation, the downsampling layer, and provide evidence that robust models have learned to downsample more accurately and suffer significantly less from aliasing than baseline models.  

[PDF](https://openreview.net/forum?id=vKc1mLxBebP) 

You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>

