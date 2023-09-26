---
title: "<span class='header-marking'>4th Visual Inductive Priors for Data-Efficient Deep Learning Workshop</span>"
layout: splash
header:
  overlay_image: assets/images/header_background_centered.png
excerpt: "<span class='header-marking'>ICCV 2023 @ Room E03 (Poster room W02) </span><br/><span class='header-marking'>Monday October 2nd 2023, 8:45 - 13:00</span>"
intro:
  - excerpt: 'Saving data by adding visual knowledge priors to Deep Learning.'
feature_row:
  - image_path: assets/images/callforpapers.png
    alt: "placeholder image 2"
    title: "Call for papers"
    excerpt: |
      We showcase original works on data-efficient computer vision through live oral talks and a poster session.

      **Papers available** on OpenReview.
    url: "https://openreview.net/group?id=thecvf.com/ICCV/2023/Workshop/VIPriors"
    btn_label: "OpenReview"
    btn_class: "btn--primary"
  - image_path: assets/images/poster.png
    alt: "placeholder image 2"
    title: "Call for posters"
    excerpt: |
      We invite researchers to present their recent published works on data-efficient computer vision as a poster.

      **Submission deadline**: September 23rd, 2023
    url: "call-for-papers/#call-for-posters"
    btn_label: "Call for posters"
    btn_class: "btn--primary"
  - image_path: assets/images/challenge.png
    title: "VIPriors challenges"
    excerpt: |
      We host two data efficieny challenges on detection and segmentation.

      **Technical reports due**: September 11th, 2023
    url: "challenges"
    btn_label: "Participate!"
    btn_class: "btn--primary"
organizers_row:
  - image_path: assets/images/JanVanGemert.jpg
    alt: "Jan van Gemert"
    title: "Jan van Gemert"
    excerpt: "Delft University of Technology"
    url: "https://jvgemert.github.io"
    btn_label: "Website"
    btn_class: "btn--default"
  - image_path: assets/images/EfstratiosGavves.jpg
    alt: "Efstratios Gavves"
    title: "Efstratios Gavves"
    excerpt: "University of Amsterdam"
    url: "https://www.egavves.com/"
    btn_label: "Website"
    btn_class: "btn--default"
  - image_path: assets/images/NergisTomen.jpg
    alt: "Nergis Tömen"
    title: "Nergis Tömen"
    excerpt: "Delft University of Technology"
    url: "https://www.tudelft.nl/ewi/over-de-faculteit/afdelingen/intelligent-systems/pattern-recognition-bioinformatics/computer-vision-lab/people/nergis-toemen"
    btn_label: "Website"
    btn_class: "btn--default"
  - image_path: assets/images/HadiJamaliRad.jpeg
    alt: "Hadi Jamali-Rad"
    title: "Hadi Jamali-Rad"
    excerpt: "Delft University of Technology, Shell"
    url: "https://sites.google.com/view/jamalirad/home"
    btn_label: "Website"
    btn_class: "btn--default"
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
    url: "https://www.tudelft.nl/ewi/over-de-faculteit/afdelingen/intelligent-systems/pattern-recognition-bioinformatics/computer-vision-lab/people/osman-semih-kayhan"
    excerpt: "Bosch Security Systems B.V."
    btn_label: "Website"
    btn_class: "btn--default"
  - image_path: assets/images/LorenzoBrigato.jpeg
    alt: "Lorenzo Brigato"
    title: "Lorenzo Brigato"
    excerpt: "ARTORG"
    url: "https://sites.google.com/diag.uniroma1.it/lorenzobrigato"
    btn_label: "Website"
    btn_class: "btn--default"
speakers_row:
  - image_path: /assets/images/StephanAlaniz.png
    alt: "Stephan Alaniz"
    title: "Stephan Alaniz"
    excerpt: "University of Tübingen"
    url: "https://www.eml-unitue.de/people/stephan-alaniz"
    btn_label: "Website"
    btn_class: "btn--default"
  - image_path: /assets/images/SubhransuMaji.jpg
    alt: "Subhransu Maji"
    title: "Subhransu Maji"
    excerpt: "University of Massachusetts"
    url: "https://people.cs.umass.edu/~smaji/"
    btn_label: "Website"
    btn_class: "btn--default"
  - image_path: /assets/images/ErikBekkers.jpg
    alt: "Erik Bekkers"
    title: "Erik Bekkers"
    excerpt: "University of Amsterdam"
    url: "https://ebekkers.github.io"
    btn_label: "Website"
    btn_class: "btn--default"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

## About the workshop

Data is fueling deep learning, yet it is costly to gather and to annotate. Training on massive datasets has a huge energy consumption adding to our carbon footprint. In addition, there are only a select few deep learning behemoths which have billions of data points and thousands of expensive deep learning hardware GPUs at their disposal. This workshop focuses on how to pre-wire deep networks with generic visual inductive innate knowledge structures, which allows to incorporate hard won existing generic knowledge. Visual inductive priors are data efficient: what is built-in no longer has to be learned, saving valuable training data.

Excellent recent research investigates data efficiency in deep networks by exploiting other data sources through unsupervised learning, re-using existing datasets, or synthesizing artificial training data. However, not enough attention is given on how to overcome the data dependency by adding prior knowledge to deep nets.  As a consequence, all knowledge has to be (re-)learned implicitly from data, making deep networks hard to understand black boxes which are susceptible to dataset bias requiring huge datasets and compute resources.  This workshop aims to remedy this gap by investigating how to flexibly pre-wire deep networks with generic visual innate knowledge structures, which allows to incorporate hard won existing  knowledge from physics such as light reflection or geometry.

The great power of deep neural networks is their incredible flexibility to learn. The direct consequence of such power, is that small datasets can simply be memorized and the network will likely not generalize to unseen data. Regularization aims to prevent such over-fitting by adding constraints to the learning process. Much work is done on regularization of internal network properties and architectures. In this workshop we focus on regularization methods based on innate priors. There is strong evidence that an innate prior benefits deep nets: adding convolution to deep networks yields a convolutional deep neural network (CNN) which is hugely successful and has permeated the entire field. While convolution was initially applied on images, it is now generalized to graph networks, speech, language,  3D data, video, etc. Convolution models translation invariance in images: an object may occur anywhere in the image, and thus instead of learning parameters at each location in the image, convolution allows to only consider local relations, yet, share parameters over all image locations. This allows a strong reduction in both number of parameters and examples to learn from. This workshop aims to further the great success of convolution, exploiting innate regularizing structures yielding a significant reduction of training data.

<!-- _This workshop is organized in collaboration with [**SynergySports**](https://synergysports.com/). SynergySports is co-organizing [the VIPriors 2021 challenges](challenges). Head over to the challenges page to find out more!_ -->

## Program

**Location: ICCV 2023 @ Room E03 (Poster room W02)**

| CEST | |
| -- | -- | -- | -- | -- |
| 8:45 | Opening | Announcing challenge winners. |
| 9:00 | Invited talk: Erik Bekkers | *Grounded representation learning through equivariant deep learning* |
| 9:45 | Oral presentation #1: Jayaraman J. Thiagarajan | *[InterAug: A Tuning-Free Augmentation Policy for Data-Efficient and Robust Object Detection](https://openreview.net/forum?id=Ole2LywcNw)* |
| 9:55 | Oral presentation #2: Yeskendir Koishekenov | *[Geometric Contrastive Learning](https://openreview.net/forum?id=cE4BY5XrzR)* |
| 10:05 | Oral presentation #3: Ombretta Strafforello | *[Video BagNet: Short Temporal Receptive Fields Increase Robustness in Long-Term Action Recognition](https://openreview.net/forum?id=pnMwklZdcM)* |
| 10:15 | Oral presentation #4: Pranjay Shyam | *[Adversarial Auto-Augmentation for Data-Efficient Single Image Dehazing](https://openreview.net/forum?id=Ll3ZTe0DNX)* |
| 10:25 | Coffee break | |
| 10:35 | Poster session | [Accepted posters](https://openreview.net/group?id=thecvf.com/ICCV/2023/Workshop/VIPriors) |
| 11:30 | Invited talk: Subhransu Maji | *Learning representations by convex decompositions* |
| 12:15 | Invited talk: Stephan Alaniz | *Seeking simple explanations through shape priors* |
| 13:00 | Closing remarks | |

## Invited speakers

{% include feature_row id="speakers_row" %}

## Organizers

{% include feature_row id="organizers_row" %}

### Contact

Email us at vipriors-ewi AT tudelft DOT nl
