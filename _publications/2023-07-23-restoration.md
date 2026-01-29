---
title: "On the unreasonable vulnerability of transformers for image restoration -- and an easy fix"
collection: publications
permalink: /2023-10-23-restoration
date: 2023-10-23
venue: 'International Conference on Computer Vision Workshops'
paperurl: 'https://openaccess.thecvf.com/content/ICCV2023W/AROW/papers/Agnihotri_On_the_Unreasonable_Vulnerability_of_Transformers_for_Image_Restoration_-_ICCVW_2023_paper.pdf'
authors: 'Shashank Agnihotri, Kanchana Vaishnavi Gandikota, <b>Julia Grabinski</b>, Paramanand Chandramouli, Margret Keuper'
bibtex: true
teaser: /previews/restoration.png
---
{{ page.authors }}

<img class="pub_teaser" src="../images/previews/restoration.png" alt="Teaser Image" title="teaser" />

## Abstract 

Following their success in visual recognition tasks, Vision Transformers (ViTs) are being increasingly employed for image restoration. As a few recent works claim that ViTs for image classification also have better robustness properties, we investigate whether the improved adversarial robustness of ViTs extends to image restoration. We consider the recently proposed Restormer model, as well as NAFNet and the" Baseline network" which are both simplified versions of a Restormer. We use Projected Gradient Descent (PGD) and CosPGD for our robustness evaluation. Our experiments are performed on real-world images from the GoPro dataset for image deblurring. Our analysis indicates that contrary to as advocated by ViTs in image classification works, these models are highly susceptible to adversarial attacks. We attempt to find an easy fix and improve their robustness through adversarial training. While this yields a significant increase in robustness for Restormer, results on other networks are less promising. Interestingly, we find that the design choices in NAFNet and Baselines, which were based on iid performance, and not on robust generalization, seem to be at odds with the model robustness.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

## Bibtex 
 
@InProceedings{Agnihotri_2023_ICCV,
    author    = {Agnihotri, Shashank and Gandikota, Kanchana Vaishnavi and Grabinski, Julia and Chandramouli, Paramanand and Keuper, Margret},
    title     = {On the Unreasonable Vulnerability of Transformers for Image Restoration - and an easy fix},
    booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV) Workshops},
    month     = {October},
    year      = {2023},
    pages     = {3707-3717}
}

