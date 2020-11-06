---
title: "Unsupervised Domain Adaptation for Semantic Segmentation of NIR Images through Generative Latent Search"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
date: 2020-06-01
venue: '16th European Conference on Computer Vision (ECCV 2020) [Spotlight]'
paperurl: 'https://arxiv.org/abs/2006.08696'
citation: 'Prashant Pandey*, Aayush Kumar Tyagi*, Sameer Ambekar, Prathosh AP. 2020 &quot;Unsupervised Domain Adaptation for Semantic Segmentation of NIR Images through Generative Latent Search. &quot; <i>16th European Conference on Computer Vision (ECCV 2020) </i>'
---
The conventional approaches project the data points into a "bias neutral" space using adversarial methods. We propose to transfer the bias from the source to the target domain. The latent space of a generative model, learnt on the source domain, is employed to find the "clones" for the target samples. As the "clones" are sampled from the source distribution, an oracle classifier/segmentation model learnt only on source, will interpret these "clones" of target samples in a better way, thereby reducing the domain shift. The proposed method guarantees to reduce the shift.

If we can infinitely sample from the generative latent space, then under a distance metric, target samples approximates to the source domain. The proposed method is shown to reduce shift on specific problem settings and on standard datasets as well.

The paper has been accepted as a Spotlight paper (Top 5% of accepted papers) at ECCV 2020.


Project page : https://glss-uda.github.io/
Code : https://github.com/ambekarsameer96/GLSS
