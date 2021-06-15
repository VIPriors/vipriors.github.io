---
title: "<span class='header-marking'>2nd Visual Inductive Priors for Data-Efficient Deep Learning Workshop</span>"
layout: splash
header:
  overlay_image: assets/images/header_background_centered.png
  # video:
  #   id: JuZliqT2yxg
  #   provider: youtube
excerpt: "<span class='header-marking'>ICCV 2021</span><br/><span class='header-marking'>11 October 2021</span>"
intro:
  - excerpt: 'Saving data by adding visual knowledge priors to Deep Learning.'
feature_row:
  - image_path: /assets/images/callforpapers.png
    alt: "placeholder image 2"
    title: "Call for papers"
    excerpt: |
      We invite researchers to submit their recent work on data-efficient computer vision.
      <ul>
      <li>July 23, 2021 - Submission deadline</li>
      <li>Aug 7, 2021 - Author notifications</li>
      <li>Aug 14, 2021 - Camera ready deadline</li>
      </ul>
      All deadlines are 23:59 CEST.

    url: "#call-for-papers"
    btn_label: "Call for Papers"
    btn_class: "btn--primary"
  - image_path: /assets/images/poster.png
    alt: "placeholder image 2"
    title: "Present a poster"
    excerpt: |
      We invite researchers to present their recent published works on data-efficient computer vision as a poster at our workshop. This may include works published at the main ICCV 2021 conference paper track.
      <ul>
      <li>Oct 1, 2021 - Submission deadline</li>
      </ul>
      All deadlines are 23:59 CEST.
    url: "#posters"
    btn_label: "Call for Posters"
    btn_class: "btn--primary"
  - image_path: /assets/images/challenge.png
    title: "VIPriors challenges"
    excerpt: |
      Participate in our data efficieny challenges on action recognition, classification, detection, segmentation and object tracking.
      <ul>
      <li>June 30, 2021 - Challenges open</li>
      <li>Sep 24, 2021 - Challenges dealine</li>
      <li>Oct 1, 2021 - Technical reports due</li>
      </ul>
      All deadlines are 23:59 CEST.
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

## About the workshop

Data is fueling deep learning, yet it is costly to gather and to annotate. Training on massive datasets has a huge energy consumption adding to our carbon footprint. In addition, there are only a select few deep learning behemoths which have billions of data points and thousands of expensive deep learning hardware GPUs at their disposal. This workshop focuses on how to pre-wire deep networks with generic visual inductive innate knowledge structures, which allows to incorporate hard won existing generic knowledge. Visual inductive priors are data efficient: what is built-in no longer has to be learned, saving valuable training data.

Excellent recent research investigates data efficiency in deep networks by exploiting other data sources through unsupervised learning, re-using existing datasets, or synthesizing artificial training data. However, not enough attention is given on how to overcome the data dependency by adding prior knowledge to deep nets.  As a consequence, all knowledge has to be (re-)learned implicitly from data, making deep networks hard to understand black boxes which are susceptible to dataset bias requiring huge datasets and compute resources.  This workshop aims to remedy this gap by investigating how to flexibly pre-wire deep networks with generic visual innate knowledge structures, which allows to incorporate hard won existing  knowledge from physics such as light reflection or geometry.

The great power of deep neural networks is their incredible flexibility to learn. The direct consequence of such power, is that small datasets can simply be memorized and the network will likely not generalize to unseen data. Regularization aims to prevent such over-fitting by adding constraints to the learning process. Much work is done on regularization of internal network properties and architectures. In this workshop we focus on regularization methods based on innate priors. There is strong evidence that an innate prior benefits deep nets: adding convolution to deep networks yields a convolutional deep neural network (CNN) which is hugely successful and has permeated the entire field. While convolution was initially applied on images, it is now generalized to graph networks, speech, language,  3D data, video, etc. Convolution models translation invariance in images: an object may occur anywhere in the image, and thus instead of learning parameters at each location in the image, convolution allows to only consider local relations, yet, share parameters over all image locations. This allows a strong reduction in both number of parameters and examples to learn from. This workshop aims to further the great success of convolution, exploiting innate regularizing structures yielding a significant reduction of training data.

## Workshop program

Our program will include several keynotes (TBA) as well as oral presentations of the top works submitted to the paper track.

<!-- | Time (UTC+1) | | |
| -- | -- | -- |
| 8:00 / 18:00  | Keynote session     | Panel discussion with [invited speakers](#invited-speakers) + Q&A                         |
| 8:40 / 18:40   | *Break*        |                                                |
| 8:45 / 18:45  | Oral session | [Oral presentations](#oral-session)                             |
| 9:10 / 19:10 |              | Q&A                                            |
| 9:25 / 19:25 | Challenges           | [Awards & winners presentations](challenges)               |
| 9:35 / 19:35 | Poster session      | [Poster presentations](#poster-session)             |
| 9:45 / 19:45 |              | Q&A (for posters & challenges)              |
| 9:50 / 19:50 |              | [External poster presentations](#external-poster-session)                  |
| 9:55 / 19:55 | *Closing*      |                          | -->

*Date and times for the live session are TBA (pending ICCV instructions).*

## Invited speakers
*To be announced.*
{% include feature_row id="speakers_row" %}

## Organizers

{% include feature_row id="organizers_row" %}

### Contact

Email us at vipriors-ewi AT tudelft DOT nl
