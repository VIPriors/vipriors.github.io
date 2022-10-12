---
title: "<span class='header-marking'>3rd Visual Inductive Priors for Data-Efficient Deep Learning Workshop</span>"
layout: splash
header:
  overlay_image: assets/images/header_background_centered.png
excerpt: "<span class='header-marking'>ECCV 2022</span><br/><span class='header-marking'>Monday October 24th 2022, 9:00 -  13:00</span><br /><span class='header-marking'>David Intercontinental Hotel, Salon J</span>"
intro:
  - excerpt: 'Saving data by adding visual knowledge priors to Deep Learning.'
feature_row:
  - image_path: assets/images/callforpapers.png
    alt: "placeholder image 2"
    title: "Accepted papers"
    excerpt: |
      We showcase original works on data-efficient computer vision through live oral talks and a poster session.

      **Decisions are out.**
    url: "call-for-papers"
    btn_label: "Accepted Papers"
    btn_class: "btn--primary"
  - image_path: assets/images/poster.png
    alt: "placeholder image 2"
    title: "Accepted posters"
    excerpt: |
      We invite researchers to present their recent published works on data-efficient computer vision as a poster.

      **Decisions are out.**
    url: "call-for-papers/#call-for-posters"
    btn_label: "Accepted posters"
    btn_class: "btn--primary"
  - image_path: assets/images/challenge.png
    title: "VIPriors challenges"
    excerpt: |
      We host four data efficieny challenges on action recognition, classification, detection and segmentation.

      **Winners will be announced at ECCV**.
    url: "challenges"
    btn_label: "More information"
    btn_class: "btn--primary"
organizers_row:
  - image_path: assets/images/JanVanGemert.jpg
    alt: "Jan van Gemert"
    title: "Jan van Gemert"
    excerpt: "Delft University of Technology"
    url: "https://jvgemert.github.io"
  - image_path: /assets/images/EkinCubuk.jpg
    alt: "Ekin Dogus Cubuk"
    title: "Ekin Dogus Cubuk"
    excerpt: "Google Research"
    url: "https://research.google/people/EkinDogusCubuk/"
    btn_label: "Website"
    btn_class: "btn--default"
  - image_path: assets/images/NergisTomen.jpg
    alt: "Nergis Tömen"
    title: "Nergis Tömen"
    excerpt: "Delft University of Technology"
  - image_path: assets/images/AttilaLengyel.jpg
    alt: "Attila Lengyel"
    title: "Attila Lengyel"
    excerpt: "Delft University of Technology"
    url: "https://attila94.github.io"
    btn_label: "Website"
    btn_class: "btn--default"
  - image_path: assets/images/Robert-JanBruintjes.jpg
    alt: "Robert-Jan Bruintjes"
    title: "Robert-Jan Bruintjes"
    excerpt: "Delft University of Technology"
    url: "https://rjbruin.github.io"
    btn_label: "Website"
    btn_class: "btn--default"
  - image_path: assets/images/OsmanKayhan.png
    alt: "Osman Semih Kayhan"
    title: "Osman Semih Kayhan"
    excerpt: "Bosch Security Systems B.V."
  - image_path: assets/images/MarcosBaptistaRios.jpg
    alt: "Marcos Baptista Ríos"
    title: "Marcos Baptista Ríos"
    excerpt: "Alice Biometrics S.L."
  - image_path: assets/images/LorenzoBrigato.jpeg
    alt: "Lorenzo Brigato"
    title: "Lorenzo Brigato"
    excerpt: "Sapienza University of Rome"
speakers_row:
  - image_path: /assets/images/StephaneMallat.jpg
    alt: "Stephane Mallat"
    title: "Stephane Mallat"
    excerpt: "Collège de France"
    url: "https://www.di.ens.fr/~mallat/"
    btn_label: "Website"
    btn_class: "btn--default"
  - image_path: /assets/images/DeviParikh.jpg
    alt: "Devi Parikh"
    title: "Devi Parikh"
    excerpt: "FAIR, Georgia Tech"
    url: "https://faculty.cc.gatech.edu/~parikh/"
    btn_label: "Website"
    btn_class: "btn--default"
  - image_path: /assets/images/EfstratiosGavves.jpg
    alt: "Efstratios Gavves"
    title: "Efstratios Gavves"
    excerpt: "University of Amsterdam, Ellogon.AI"
    url: "https://egavves.github.io/#about"
    btn_label: "Website"
    btn_class: "btn--default"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include twitter_sidebar %}

## About the workshop

Data is fueling deep learning, yet it is costly to gather and to annotate. Training on massive datasets has a huge energy consumption adding to our carbon footprint. In addition, there are only a select few deep learning behemoths which have billions of data points and thousands of expensive deep learning hardware GPUs at their disposal. This workshop focuses on how to pre-wire deep networks with generic visual inductive innate knowledge structures, which allows to incorporate hard won existing generic knowledge. Visual inductive priors are data efficient: what is built-in no longer has to be learned, saving valuable training data.

Excellent recent research investigates data efficiency in deep networks by exploiting other data sources through unsupervised learning, re-using existing datasets, or synthesizing artificial training data. However, not enough attention is given on how to overcome the data dependency by adding prior knowledge to deep nets.  As a consequence, all knowledge has to be (re-)learned implicitly from data, making deep networks hard to understand black boxes which are susceptible to dataset bias requiring huge datasets and compute resources.  This workshop aims to remedy this gap by investigating how to flexibly pre-wire deep networks with generic visual innate knowledge structures, which allows to incorporate hard won existing  knowledge from physics such as light reflection or geometry.

The great power of deep neural networks is their incredible flexibility to learn. The direct consequence of such power, is that small datasets can simply be memorized and the network will likely not generalize to unseen data. Regularization aims to prevent such over-fitting by adding constraints to the learning process. Much work is done on regularization of internal network properties and architectures. In this workshop we focus on regularization methods based on innate priors. There is strong evidence that an innate prior benefits deep nets: adding convolution to deep networks yields a convolutional deep neural network (CNN) which is hugely successful and has permeated the entire field. While convolution was initially applied on images, it is now generalized to graph networks, speech, language,  3D data, video, etc. Convolution models translation invariance in images: an object may occur anywhere in the image, and thus instead of learning parameters at each location in the image, convolution allows to only consider local relations, yet, share parameters over all image locations. This allows a strong reduction in both number of parameters and examples to learn from. This workshop aims to further the great success of convolution, exploiting innate regularizing structures yielding a significant reduction of training data.

<!-- _This workshop is organized in collaboration with [**SynergySports**](https://synergysports.com/). SynergySports is co-organizing [the VIPriors 2021 challenges](challenges). Head over to the challenges page to find out more!_ -->

## Program

| GMT | IDT (GMT+3) | | |
| -- | -- | -- | -- | -- |
| 6:00 | 9:00 | Opening | Challenge winners will be announced. |
| 6:15 | 9:15 | Invited talk: Stephane Mallat | |
| 7:00 | 10:00 | Oral presentations | [Accepted orals](call-for-papers/#orals) |
| 7:30 | 10:30 | Poster session | [Accepted posters](call-for-papers/#posters) |
| 8:30 | 11:30 | Invited talk: Devi Parikh | |
| 9:15 | 12:15 | Invited talk: Efstratios Gavves | |
| 10:00 | 13:00 | Closing | |

## Invited speakers

<!-- _Speakers are TBA._ -->

{% include feature_row id="speakers_row" %}

## Organizers

{% include feature_row id="organizers_row" %}

### Contact

Email us at vipriors-ewi AT tudelft DOT nl
