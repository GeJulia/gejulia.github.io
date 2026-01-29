---
title: "Aliasing coincides with CNNs vulnerability towards adversarial attacks"
collection: publications
permalink: /22022-02-01-aliasing
date: 2022-02-01
venue: 'AAAI-22 Workshop on Adversarial Machine Learning and Beyond'
paperurl: 'https://openreview.net/pdf?id=vKc1mLxBebP'
authors: '<b>Julia Grabinski</b>, Janis Keuper, Margret Keuper'
bibtex: true
teaser: /previews/aliasing.png
---
{{ page.authors }}

<img class="pub_teaser" src="../images/previews/aliasing.png" alt="Teaser Image" title="teaser" />

## Abstract 

Many commonly well-performing convolutional neural network models have shown to be susceptible to input data perturbations, indicating a low model robustness. Adversarial attacks are thereby specifically optimized to reveal model weaknesses, by generating small, barely perceivable image perturbations that flip the model prediction. Robustness against attacks can be gained for example by using adversarial examples during training, which effectively reduces the measurable model attackability. In contrast, research on analyzing the source of a model’s vulnerability is scarce. In this paper, we analyze adversarially trained, robust models in the context of a specifically suspicious network operation, the downsampling layer, and provide evidence that robust models have learned to downsample more accurately and suffer significantly less from aliasing than baseline models.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

## Bibtex 
 
  @inproceedings{
  grabinski2022aliasing,
  title={Aliasing coincides with {CNN}s vulnerability towards adversarial attacks},
  author={Julia Grabinski and Janis Keuper and Margret Keuper},
  booktitle={The AAAI-22 Workshop on Adversarial Machine Learning and Beyond},
  year={2022},
  url={https://openreview.net/forum?id=vKc1mLxBebP}
  }
