---
title: "<span class='header-marking'>2nd Visual Inductive Priors for Data-Efficient Deep Learning Workshop</span>"
layout: splash
header:
  overlay_image: assets/images/header_background_centered.png
  # video:
  #   id: JuZliqT2yxg
  #   provider: youtube
excerpt: "<span class='header-marking'>ICCV 2021</span><br/><span class='header-marking'>11 October 2021, afternoon</span>"
intro:
  - excerpt: 'Saving data by adding visual knowledge priors to Deep Learning.'
feature_row:
  - image_path: /assets/images/callforpapers.png
    alt: "placeholder image 2"
    title: "Call for papers"
    excerpt: |
      We showcase recent work on data-efficient computer vision: [OpenReview site](https://openreview.net/group?id=thecvf.com/ICCV/2021/Workshop/VIPriors).

    url: "call-for-papers"
    btn_label: "Call for Papers"
    btn_class: "btn--primary"
  - image_path: /assets/images/poster.png
    alt: "placeholder image 2"
    title: "Present a poster"
    excerpt: |
      We invite researchers to present their recent published works on data-efficient computer vision as a poster at our workshop. This may include works published at the main ICCV 2021 conference paper track.
    url: "call-for-papers/#call-for-posters"
    btn_label: "Call for Posters"
    btn_class: "btn--primary"
  - image_path: /assets/images/challenge.png
    title: "VIPriors challenges"
    excerpt: |
      Participate in our data efficieny challenges on action recognition, classification, detection, segmentation and object tracking.
      <ul>
      <li>Sep 24, 2021 - Challenges dealine</li>
      <li>Oct 1, 2021 - Technical reports due</li>
      </ul>
      All deadlines are 23:59 GMT.
    url: "challenges"
    btn_label: "Read More"
    btn_class: "btn--primary"
organizers_row:
  - image_path: /assets/images/JanVanGemert.jpg
    alt: "Jan van Gemert"
    title: "Jan van Gemert"
    excerpt: "Delft University of Technology"
    url: "https://jvgemert.github.io/"
    btn_label: "Website"
    btn_class: "btn--default"
  - image_path: /assets/images/MatthiasBethge.jpg
    alt: "Matthias Bethge"
    title: "Matthias Bethge"
    excerpt: "Bethge Lab"
    url: "http://bethgelab.org/people/matthias/"
    btn_label: "Website"
    btn_class: "btn--default"
  - image_path: /assets/images/NergisTomen.jpg
    alt: "Nergis Tömen"
    title: "Nergis Tömen"
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
    url: "https://rjbruin.github.io"
    btn_label: "Website"
    btn_class: "btn--default"
  - image_path: /assets/images/OsmanKayhan.png
    alt: "Osman Semih Kayhan"
    title: "Osman Semih Kayhan"
    excerpt: "Bosch Security Systems B.V."
  - image_path: /assets/images/MarcosBaptistaRios.jpg
    alt: "Marcos Baptista Ríos"
    title: "Marcos Baptista Ríos"
    excerpt: "Gradiant"
speakers_row:
  - image_path: /assets/images/AnimaAnandkumar.png
    alt: "Anima Anandkumar"
    title: "Anima Anandkumar"
    excerpt: "Caltech, NVIDIA"
    url: "http://tensorlab.cms.caltech.edu/users/anima/"
    btn_label: "Website"
    btn_class: "btn--default"
  - image_path: /assets/images/EkinCubuk.jpg
    alt: "Ekin Dogus Cubuk"
    title: "Ekin Dogus Cubuk"
    excerpt: "Google Research"
    url: "https://research.google/people/EkinDogusCubuk/"
    btn_label: "Website"
    btn_class: "btn--default"
  - image_path: /assets/images/ChelseaFinn.jpg
    alt: "Chelsea Finn"
    title: "Chelsea Finn"
    excerpt: "Stanford University"
    url: "https://ai.stanford.edu/~cbfinn/"
    btn_label: "Website"
    btn_class: "btn--default"
  - image_path: /assets/images/MaxWelling.jpg
    alt: "Max Welling"
    title: "Max Welling"
    excerpt: "University of Amsterdam, Qualcomm"
    url: "https://staff.fnwi.uva.nl/m.welling/"
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

_This workshop is organized in collaboration with [**SynergySports**](https://synergysports.com/). SynergySports is co-organizing [the VIPriors 2021 challenges](/challenges). Head over to the challenges page to find out more!_

## Workshop program

| EDT (UTC-4) | UTC | CEST (UTC+2) | CST (UTC+8) | | |
| --    | --    | --    | --   | -- |
| 13:00 | 17:00 | 19:00 | 01:00 | **Opening** | Challenge winners will be announced. |
| 13:15 | 17:15 | 19:15 | 01:15 | **Invited talk: Chelsea Finn** |  |
| 13:45 | 17:45 | 19:45 | 01:45 | **Invited talk: Max Welling** |  |
| 14:15 | 18:15 | 20:15 | 02:15 | **Invited talks Q&A** |  |
| 14:30 | 18:30 | 20:30 | 02:30 | **Break** | |
| 14:40 | 18:40 | 20:40 | 02:40 | **Oral presentations** | Three 10-minute presentations. |
| 15:10 | 19:10 | 21:10 | 03:10 | **Poster session** | All accepted works will be presented on a Gather.Town-like platform (platform TBD). |
| 16:00 | 20:00 | 22:00 | 04:00 | **Invited talk: Anima Anandkumar** |  |
| 16:30 | 20:30 | 22:30 | 04:30 | **Invited talk: Ekin Dogus Cubuk** |  |
| 17:00 | 21:00 | 23:00 | 05:00 | **Invited talks Q&A** |  |
| 17:15 | 21:15 | 23:15 | 05:15 (est.) | **Conclusion** | |

## Invited speakers

{% include feature_row id="speakers_row" %}

## Organizers

{% include feature_row id="organizers_row" %}

### Contact

Email us at vipriors-ewi AT tudelft DOT nl
