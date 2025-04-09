---
title: "Sifting through the Haystack - Efficiently Finding Rare Animal Behaviors in Large-Scale Datasets"
collection: publications
category: conferences
permalink: /publication/2025-02-01-sifting-through-the-haystack-efficiently-finding-rare-animal-behaviors-in-large-scale-datasets
excerpt: ''
date: 2025-02-01
venue: 'Proceedings of the Winter Conference on Applications of Computer Vision (WACV)'
slidesurl: #''
paperurl: 'https://openaccess.thecvf.com/content/WACV2025/papers/Bar_Sifting_through_the_Haystack_-_Efficiently_Finding_Rare_Animal_Behaviors_WACV_2025_paper.pdf'
bibtexurl: 'http://academicpages.github.io/files/bib3.bib'
citation: 'Bar, Shir; Hirschorn, Or; Holzman, Roi; Avidan, Shai. (2025). "Sifting through the Haystack - Efficiently Finding Rare Animal Behaviors in Large-Scale Datasets." <i>Proceedings of the Winter Conference on Applications of Computer Vision (WACV)</i>. 6290-6299.'
---
[pdf](/files/Bar_Sifting_through_the_Haystack_-_Efficiently_Finding_Rare_Animal_Behaviors_WACV_2025_paper.pdf) |
[supplementary](/files/Bar_Sifting_through_the_WACV_2025_supplemental.pdf) 
[code](https://github.com/shir3bar/SiftingTheHaystack)

**Abstract**
In the study of animal behavior, researchers often record long continuous videos, accumulating into large-scale datasets. 
However, the behaviors of interest are often rare compared to routine behaviors. 
This incurs a heavy cost on manual annotation,
forcing users to sift through many samples before finding their needles. 
We propose a pipeline to efficiently sample rare behaviors from large datasets, enabling the creation of training datasets for rare behavior classifiers. Our method only needs an unlabeled animal pose or acceleration dataset as input and makes no assumptions regarding the type, number, or characteristics of the rare behaviors.

Our pipeline is based on a recent graph-based anomaly detection model for human behavior, which we apply to this new data domain. 
It leverages anomaly scores to automatically label normal samples while directing human annotation efforts toward anomalies.
In research data, anomalies may come from many different sources (e.g., signal noise versus true rare instances).
Hence, the entire labeling budget is focused on the abnormal classes, letting the user review and label samples according to their needs. 


We tested our approach on three datasets of freely-moving animals, acquired in the laboratory and the field.
We found that graph-based models are particularly useful when studying motion-based behaviors in animals, yielding good results while using a small labeling budget.
Our method consistently outperformed traditional random sampling, offering an average improvement of 70% in performance and creating datasets even when the behavior of interest was only 0.02% of the data. Even when the performance gain was minor (e.g., when the behavior is not rare), our method still reduced the annotation effort by half. 

