---
title: "Sifting through a haystack - efficiently finding rare behaviors in big datasets"
collection: talks
type: "Talk"
permalink: /talks/2025-sicb-haystack-talk
venue: "Society of Integrative and Comparative Biology (SICB)"
date: 2025-01-01
location: "Atlanta, GA, USA"
---
[abstract](/talks/2025-sicb-haystack-talk)

**Abstract** Rare events play an important role in animal ecology. Behaviors such as evading predators or reproduction can occur rarely but are critical for the animal’s fitness. The difficulty in collecting sufficient observations of these rare behaviors hinders their investigation, often hampering our ability to test hypotheses regarding their ecology. Attempts to automate the detection of rare behaviors using Machine Learning (ML) methods face difficulties because it is difficult to generate the large, labeled datasets required to train these models. 
We present a method that first uses a no-label ML model to search the data for anomalous behaviors. Based on this search, labeled datasets can be built with high efficiency to train the main ML model used to detect rare behaviors. We adapt graph-based convolutional neural networks used for human behavior and show that they are well-suited for analyzing the kinematics of animal behavior. We tested our approach on 3 datasets, two featuring larval fish behavior in the laboratory, and an additional dataset of accelerometry acquired from meerkats in the wild. Our results show that, for behaviors that account for <1.5% of the observations, our method is twice more accurate than that trained using a traditional approach. Importantly, we find that the graph-based networks produce good results using much smaller datasets, by allowing the model to focus on animal kinematics rather than the filming environment.

