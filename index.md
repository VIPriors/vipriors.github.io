---
title: "1st Visual Inductive Priors for Data-Efficient Deep Learning Workshop"
layout: splash
header:
  overlay_image: https://eccv2020.eu/wp-content/uploads/2019/10/ECCV-HEADER-Main.jpg
  caption: "Photo credit: [**ECCV 2020**](https://eccv2020.eu)"
excerpt: "ECCV 2020 <br/> 2x August 2020, Glasgow UK"
intro:
  - excerpt: 'This workshop focuses on how to pre-wire deep networks with generic visual inductive innate knowledge structures, which allows to incorporate hard won existing generic knowledge from physics such as light reflection or geometry. Visual inductive priors are data efficient: What is built-in no longer has to be learned, saving valuable training data.'
feature_row:
  - image_path: /assets/images/addtocal.png
    alt: "Add to calendar"
    title: "Workshop program"
    excerpt: "Half-day program with invited speakers and challenge presentations."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/callforpapers.png
    alt: "placeholder image 2"
    title: "Call for papers"
    excerpt: "We invite researchers to submit their recent work on data-efficient computer vision."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/challenge.png
    title: "VIPriors challenge"
    excerpt: "Including data-efficient **classification**, **detection**, **segmentation** and **action recognition**."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

# About the workshop

Data is fueling deep learning. Data is costly to gather and expensive to annotate. Training on massive datasets has a huge energy consumption adding to our carbon footprint. This workshop aims beyond the few very large companies that can accommodate ML on this scale to the long tail of smaller companies and universities with smaller datasets and smaller hardware clusters. We focus on data efficiency through visual inductive priors.

Excellent recent research investigates data efficiency in deep networks by exploiting other data sources such as unsupervised learning, re-using existing datasets, or synthesizing artificial training data. Not much attention is given on how to overcome the data dependency by adding prior knowledge to deep nets. As a consequence, all knowledge has to be (re-)learned implicitly from data, making deep networks hard to understand black boxes. This workshop aims to remedy this gap by investigating how to flexibly pre-wire deep networks with generic visual innate knowledge structures, which allows to incorporate hard won existing knowledge from physics such as light reflection or geometry.

## Workshop program

| Time | Event | Description |
|------|-------|-------------|
| TBD  | TBD   | TBD         |

## Call for papers

**TODO: write this**

## VIPriors Challenge

We present the "Visual Inductive Priors for Data-Efficient Computer Vision'' challenges. We offer four challenges, where models are to be trained from scratch, and we reduce the number of training samples to a fraction of the full set. The four data-deficient challenges are: 1) ImageNet classification 2) Cityscapes segmentation, 3) MS COCO object detection and 4) UFC-101 action recognition.

- We prohibit the use of other data than the provided training data, i.e., no pre-training, no transfer learning.
- These tasks were chosen to encourage any researcher to participate: no giant GPU clusters are needed.
- We will provide some simple Python tooling to accommodate data generation and submitting results. Results are to be submitted in CSV-format and evaluated on submission.
- Top contenders in the challenge should expect their submissions to be submitted to peer review to ensure reproducability.

