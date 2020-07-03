---
title: "<span class='header-marking'>1st Visual Inductive Priors for Data-Efficient Deep Learning Workshop</span>"
layout: splash
header:
  overlay_image: assets/images/header_background_centered.png
excerpt: "<span class='header-marking'>ECCV 2020</span><br/><span class='header-marking'>23 August 2020 (morning), ONLINE</span>"
intro:
  - excerpt: 'Saving data by adding visual knowledge priors to Deep Learning'
feature_row:
  - image_path: /assets/images/callforpapers.png
    alt: "placeholder image 2"
    title: "Call for papers"
    excerpt: "We invite researchers to submit their recent work on data-efficient computer vision.<br /><br />**Deadline**: July 17th"
    url: "#call-for-papers"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/poster.png
    alt: "placeholder image 2"
    title: "Present a poster"
    excerpt: "We invite researchers to present their ECCV 2020 papers on data-efficient computer vision.<br /><br />**Deadline**: August 2nd"
    url: "#posters"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/challenge.png
    title: "VIPriors challenges"
    excerpt: "Including data-efficient **action recognition**, **classification**, **detection** and **segmentation**.<br /><br />**Deadline**: July 10th"
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
  - image_path: /assets/images/AntonVanDenHengel.jpg
    alt: "dr. Anton van den Hengel"
    title: "dr. Anton van den Hengel"
    excerpt: "University of Adelaide"
    url: "https://cs.adelaide.edu.au/~hengel/"
    btn_label: "Website"
    btn_class: "btn--default"
  - image_path: /assets/images/AttilaLengyel.jpg
    alt: "Attila Lengyel"
    title: "Attila Lengyel"
    excerpt: "Delft University of Technology"
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
    excerpt: "Delft University of Technology"
  - image_path: /assets/images/MarcosBaptistaRios.jpg
    alt: "Marcos Baptista Rios"
    title: "Marcos Baptista Rios"
    excerpt: "University of Alcala"
speakers_row:
  - image_path: /assets/images/MatthiasBethge.jpg
    alt: "dr. Matthias Bethge"
    title: "dr. Matthias Bethge"
    excerpt: "Bethge Lab"
    url: "http://bethgelab.org/people/matthias/"
    btn_label: "Website"
    btn_class: "btn--default"
  - image_path: /assets/images/CharlesLeek.jpg
    alt: "prof. Charles Leek"
    title: "prof. Charles Leek"
    excerpt: "University of Liverpool"
    url: "https://www.liverpool.ac.uk/psychology/staff/charles-leek/"
    btn_label: "Website"
    btn_class: "btn--default"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include twitter_sidebar %}

# Workshop now fully online

Following the main conferences decision to move fully online our workshop will also be **fully online**. We will announced a revised program soon. Keynotes, orals and posters will go through as planned, though in an online form. Deadlines will not change, except for the deadline for submitting a poster which has been pulled forward by two weeks to August 2nd to accomodate uploading the required materials to the conference website in time.

**Please stay tuned for a full update on the new form of our workshop.**

# About the workshop

This workshop focuses on how to pre-wire deep networks with generic visual inductive innate knowledge structures, which allows to incorporate hard won existing generic knowledge from physics such as light reflection or geometry. Visual inductive priors are data efficient: What is built-in no longer has to be learned, saving valuable training data.


Data is fueling deep learning. Data is costly to gather and expensive to annotate. Training on massive datasets has a huge energy consumption adding to our carbon footprint. In addition, there are only a select few deep learning behemoths which have billions of data points and thousands of expensive deep learning hardware GPUs at their disposal. This workshop aims beyond the few very large companies to the long tail of smaller companies and universities with smaller datasets and smaller hardware clusters. We focus on data efficiency through visual inductive priors.

Excellent recent research investigates data efficiency in deep networks by exploiting other data sources such as unsupervised learning, re-using existing datasets, or synthesizing artificial training data. Not enough attention is given on how to overcome the data dependency by adding prior knowledge to deep nets.  As a consequence, all knowledge has to be (re-)learned implicitly from data, making deep networks hard to understand black boxes which are susceptible to dataset bias requiring huge data and compute resources.  This workshop aims to remedy this gap by investigating how to flexibly pre-wire deep networks with generic visual innate knowledge structures, which allows to incorporate hard won existing  knowledge from physics such as light reflection or geometry.

The great power of deep neural networks is their incredible flexibility to learn. The direct consequence of such power, is that small datasets can simply be memorized and the network will likely not generalize to unseen data. Regularization aims to prevent such over-fitting by adding constraints to the learning process. Much work is done on regularization of internal network properties and architectures. In this workshop we focus on regularization methods based on innate priors. There is strong evidence that an innate prior benefits deep nets: Adding convolution  to deep networks yields a convolutional deep neural network (CNN) which is hugely successful and has permeated the entire field. While convolution was initially applied on images, it is now generalized to graph networks, speech, language,  3D data, video, etc. Convolution models translation invariance in images: an object may occur anywhere in the image, and thus instead of learning parameters at each location in the image, convolution allows to only consider local relations, yet, share parameters over all image locations, and thus saving a huge number of parameters to learn, allowing a strong reduction in the number of examples to learn from. This workshop aims to further the great success of convolution, exploiting innate regularizing structures yielding a significant reduction of training data.

## Workshop program

Our program will include keynotes by [dr. Matthias Bethge](#invited-speakers), [prof. Charles Leek](#invited-speakers) and others (TBA), oral presentations by challenge winners and selected papers accepted to the workshop, as well as poster presentations for accepted submissions and other recent relevant works.

*The revised online workshop program will be made available as soon as possible.*

## Call for papers

We solicit submission that in the broad sense focus on data efficiency through visual inductive priors covering but not limited to the following topics:

- Improving data efficiency of Deep Computer Vision methods using prior knowledge about the task domain
- Analysis on the properties of Deep Learning representations as they relate to visual inductive priors
- Transformation-equivariant image representations, e.g. scale-equivariance, rotation-equivariance, etc.
- Color invariants/constants in Deep Learning
- Object persistence between video frames
- Shape-based representations for Deep Learning
- Texture/shape bias in Convolutional Neural Networks
- Alternative compact filter bases for Deep Learning
- Capsule Networks

**Important dates**

- Submissions open: March 1, 2020
- Submission deadline: July 17, 2020
- Notification of acceptance: July 31, 2020
- Camera-ready deadline: September 15, 2020
- Workshop: August 23, 2020

**Submission guidelines**

- Submissions must be entered in OpenReview: [link](https://openreview.net/group?id=thecvf.com/ECCV/2020/Workshop/VIPriors).
- Submissions must follow the [ECCV 2020 submission format](https://eccv2020.eu/author-instructions/).
- Reviewing will be according to double-blind format.
- Accepted papers will be published in ECCV 2020 Workshop proceedings.
- Authors of accepted papers will be invited to present their work as a poster presentation at the workshop. Authors of a selection of papers will be invited to present their work orally at the workshop.

### Posters

Authors of recent and relevant works (including works published at the main ECCV 2020 conference paper track) are invited to present a **poster** of their work at our workshop. Please [contact the organizers](#organizers) if you would like to present your work at our workshop.

**Important dates**

- Deadline: August 2, 2020

*Note that this deadline has been pulled forward by two weeks to August 2nd to accomodate uploading the required materials to the conference website in time. Organizers will contact accepted posters about hosting their posters.*

## VIPriors Challenges

We present the "Visual Inductive Priors for Data-Efficient Computer Vision'' challenges. We offer four challenges, where models are to be trained from scratch, and we reduce the number of training samples to a fraction of the full set.

Please see the [challenges page](/challenges) for submission instructions and deadlines.

## Invited speakers

{% include feature_row id="speakers_row" %}

*More speakers are to be announced.*

## Organizers

{% include feature_row id="organizers_row" %}

### Contact

Email us at vipriors-ewi AT tudelft DOT nl