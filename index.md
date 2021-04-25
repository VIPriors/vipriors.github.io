---
title: "<span class='header-marking'>2nd Visual Inductive Priors for Data-Efficient Deep Learning Workshop</span>"
layout: splash
header:
  overlay_image: assets/images/header_background_centered.png
  # video:
  #   id: JuZliqT2yxg
  #   provider: youtube
excerpt: "<span class='header-marking'>ICCV 2021</span><br/><span class='header-marking'>ONLINE</span>"
intro:
  - excerpt: 'Saving data by adding visual knowledge priors to Deep Learning'
feature_row:
  - image_path: /assets/images/callforpapers.png
    alt: "placeholder image 2"
    title: "Call for papers"
    excerpt: "We invite researchers to submit their recent work on data-efficient computer vision."
    url: "#call-for-papers"
    btn_label: "Call for Papers"
    btn_class: "btn--primary"
  - image_path: /assets/images/poster.png
    alt: "placeholder image 2"
    title: "Present a poster"
    excerpt: "We invite researchers to present their recent published works on data-efficient computer vision."
    url: "#posters"
    btn_label: "Call for Posters"
    btn_class: "btn--primary"
  - image_path: /assets/images/challenge.png
    title: "VIPriors challenges"
    excerpt: "Including data-efficient **action recognition**, **classification**, **detection** and **segmentation**."
    url: "challenges"
    btn_label: "Read More"
    btn_class: "btn--primary"
organizers_row:
  - image_path: /assets/images/JanVanGemert.jpg
    alt: "dr. Jan van Gemert"
    title: "dr. Jan van Gemert"
    excerpt: "Delft University of Technology"
    url: "https://jvgemert.github.io/"
    btn_label: "Website"
    btn_class: "btn--default"
  - image_path: /assets/images/MatthiasBethge.jpg
    alt: "dr. Matthias Bethge"
    title: "dr. Matthias Bethge"
    excerpt: "Bethge Lab"
    url: "http://bethgelab.org/people/matthias/"
    btn_label: "Website"
    btn_class: "btn--default"
  - image_path: /assets/images/NergisTomen.jpg
    alt: "dr. Nergis Tömen"
    title: "dr. Nergis Tömen"
    excerpt: "Delft University of Technology"
  - image_path: /assets/images/AttilaLengyel.jpg
    alt: "Attila Lengyel"
    title: "Attila Lengyel"
    excerpt: "Delft University of Technology"
    url: "https://attila94.github.io"
    btn_label: "Website"
    btn_class: "btn--default"
  - image_path: /assets/images/Robert-JanBruintjes.jpg
    alt: "Robert-Jan Bruintjes"
    title: "Robert-Jan Bruintjes"
    excerpt: "Delft University of Technology"
    url: "https://rjbruin.nl"
    btn_label: "Website"
    btn_class: "btn--default"
  - image_path: /assets/images/OsmanKayhan.png
    alt: "Osman Semih Kayhan"
    title: "Osman Semih Kayhan"
    excerpt: "Bosch Security Systems B.V."
  - image_path: /assets/images/MarcosBaptistaRios.jpg
    alt: "Marcos Baptista Ríos"
    title: "Marcos Baptista Ríos"
    excerpt: "University of Alcala"
# speakers_row:
#   - image_path: /assets/images/blank-photo.png
#     alt: "TBA"
#     title: "TBA"
#     excerpt: ""
#     url: ""
#     # btn_label: "Website"
#     # btn_class: "btn--default"
#   - image_path: /assets/images/blank-photo.png
#     alt: "TBA"
#     title: "TBA"
#     excerpt: ""
#     url: ""
#     # btn_label: "Website"
#     # btn_class: "btn--default"
#   - image_path: /assets/images/blank-photo.png
#     alt: "TBA"
#     title: "TBA"
#     excerpt: ""
#     url: ""
#     # btn_label: "Website"
#     # btn_class: "btn--default"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include twitter_sidebar %}

# About the workshop

This workshop focuses on how to pre-wire deep networks with generic visual inductive innate knowledge structures, which allows to incorporate hard won existing generic knowledge from physics such as light reflection or geometry. Visual inductive priors are data efficient: What is built-in no longer has to be learned, saving valuable training data.

Data is fueling deep learning. Data is costly to gather and expensive to annotate. Training on massive datasets has a huge energy consumption adding to our carbon footprint. In addition, there are only a select few deep learning behemoths which have billions of data points and thousands of expensive deep learning hardware GPUs at their disposal. This workshop aims beyond the few very large companies to the long tail of smaller companies and universities with smaller datasets and smaller hardware clusters. We focus on data efficiency through visual inductive priors.

Excellent recent research investigates data efficiency in deep networks by exploiting other data sources such as unsupervised learning, re-using existing datasets, or synthesizing artificial training data. Not enough attention is given on how to overcome the data dependency by adding prior knowledge to deep nets.  As a consequence, all knowledge has to be (re-)learned implicitly from data, making deep networks hard to understand black boxes which are susceptible to dataset bias requiring huge data and compute resources.  This workshop aims to remedy this gap by investigating how to flexibly pre-wire deep networks with generic visual innate knowledge structures, which allows to incorporate hard won existing  knowledge from physics such as light reflection or geometry.

The great power of deep neural networks is their incredible flexibility to learn. The direct consequence of such power, is that small datasets can simply be memorized and the network will likely not generalize to unseen data. Regularization aims to prevent such over-fitting by adding constraints to the learning process. Much work is done on regularization of internal network properties and architectures. In this workshop we focus on regularization methods based on innate priors. There is strong evidence that an innate prior benefits deep nets: Adding convolution  to deep networks yields a convolutional deep neural network (CNN) which is hugely successful and has permeated the entire field. While convolution was initially applied on images, it is now generalized to graph networks, speech, language,  3D data, video, etc. Convolution models translation invariance in images: an object may occur anywhere in the image, and thus instead of learning parameters at each location in the image, convolution allows to only consider local relations, yet, share parameters over all image locations, and thus saving a huge number of parameters to learn, allowing a strong reduction in the number of examples to learn from. This workshop aims to further the great success of convolution, exploiting innate regularizing structures yielding a significant reduction of training data.

## Workshop program

Our program will include several keynotes (TBA) as well as oral presentations of the top works submitted to the paper track.

*Date and times for the live session are TBA (pending ICCV instructions).*

## Call for papers

We solicit submissions that in the broad sense focus on achieving data efficiency through incorporating prior knowledge of the visual domain into network design. This includes the following topics:

- Pre-wired invariance/equivariance to symmetries, such as translation, rotation, scaling, etc.
- Parameter sharing for data efficiency
- (Meta-)learning symmetries from data
- Unsupervised learning through visual priors, e.g. contrastive learning
- Color invariants/constants in Deep Learning
- Data augmentation
- Human vision as an inspiration for data-efficient vision algorithms, e.g. reducing texture bias in Convolutional Neural Networks, modeling network operations after human vision, etc.
- Alternative data-efficient operators for Deep Learning inspired by visual inductive priors, e.g. alternative compact filter bases, Capsule Networks, etc.

Please note that this list is not exhaustive! We strongly encourage novel approaches to data efficient methods using visual prior knowledge.

*Submission instructions & deadlines are TBA.*

### Call for posters

Authors of recent and relevant works (including works published at the main ICCV 2021 conference paper track) are invited to present a **poster** of their work at our workshop.

*Submission instructions & deadlines are TBA.*

## VIPriors Challenges

We presented the "Visual Inductive Priors for Data-Efficient Computer Vision" challenges. We offered four challenges, where models are to be trained from scratch, and we reduced the number of training samples to a fraction of the full set.

Please see the [challenges page](/challenges) for the results of the challenges.

## Invited speakers

{% include feature_row id="speakers_row" %}

## Organizers

{% include feature_row id="organizers_row" %}

### Contact

Email us at vipriors-ewi AT tudelft DOT nl
