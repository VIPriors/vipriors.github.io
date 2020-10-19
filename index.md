---
title: "<span class='header-marking'>1st Visual Inductive Priors for Data-Efficient Deep Learning Workshop</span>"
layout: splash
header:
  overlay_image: assets/images/header_background_centered.png
  # video:
  #   id: JuZliqT2yxg
  #   provider: youtube
excerpt: "<span class='header-marking'>ECCV 2020</span><br/><span class='header-marking'>23 August 2020, ONLINE</span>"
intro:
  - excerpt: 'Saving data by adding visual knowledge priors to Deep Learning'
feature_row:
  - image_path: /assets/images/callforpapers.png
    alt: "placeholder image 2"
    title: "Call for papers"
    excerpt: "We invite researchers to submit their recent work on data-efficient computer vision.<br /><br />**Accepted works** are included in [the program](#workshop-program)."
    url: "#call-for-papers"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/poster.png
    alt: "placeholder image 2"
    title: "Present a poster"
    excerpt: "We invite researchers to present their recent papers on data-efficient computer vision.<br /><br />**Accepted posters** are included in [the program](#workshop-program)."
    url: "#posters"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/challenge.png
    title: "VIPriors challenges"
    excerpt: "Including data-efficient **action recognition**, **classification**, **detection** and **segmentation**.<br /><br />[**Final rankings**](https://vipriors.github.io/challenges/#final-rankings) are out now."
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
    alt: "Marcos Baptista Ríos"
    title: "Marcos Baptista Ríos"
    excerpt: "University of Alcala"
speakers_row:
  - image_path: /assets/images/MatthiasBethge.jpg
    alt: "prof. Matthias Bethge"
    title: "prof. Matthias Bethge"
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
  - image_path: /assets/images/DanielCremers.jpg
    alt: "prof. Daniel Cremers"
    title: "prof. Daniel Cremers"
    excerpt: "TU München"
    url: "https://vision.in.tum.de/members/cremers"
    btn_label: "Website"
    btn_class: "btn--default"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

# Watch the recording

{% include video id="JuZliqT2yxg" provider="youtube" %}

{% include twitter_sidebar %}

# Thanks to all for attending

We enjoyed two interesting workshop sessions at ECCV 2020. We thank all presenters for their efforts and all participants for their attention. This website will keep a record of all presented materials. We hope to see you all next year (venue TBD) for the next workshop!

# About the workshop

This workshop focuses on how to pre-wire deep networks with generic visual inductive innate knowledge structures, which allows to incorporate hard won existing generic knowledge from physics such as light reflection or geometry. Visual inductive priors are data efficient: What is built-in no longer has to be learned, saving valuable training data.

Data is fueling deep learning. Data is costly to gather and expensive to annotate. Training on massive datasets has a huge energy consumption adding to our carbon footprint. In addition, there are only a select few deep learning behemoths which have billions of data points and thousands of expensive deep learning hardware GPUs at their disposal. This workshop aims beyond the few very large companies to the long tail of smaller companies and universities with smaller datasets and smaller hardware clusters. We focus on data efficiency through visual inductive priors.

Excellent recent research investigates data efficiency in deep networks by exploiting other data sources such as unsupervised learning, re-using existing datasets, or synthesizing artificial training data. Not enough attention is given on how to overcome the data dependency by adding prior knowledge to deep nets.  As a consequence, all knowledge has to be (re-)learned implicitly from data, making deep networks hard to understand black boxes which are susceptible to dataset bias requiring huge data and compute resources.  This workshop aims to remedy this gap by investigating how to flexibly pre-wire deep networks with generic visual innate knowledge structures, which allows to incorporate hard won existing  knowledge from physics such as light reflection or geometry.

The great power of deep neural networks is their incredible flexibility to learn. The direct consequence of such power, is that small datasets can simply be memorized and the network will likely not generalize to unseen data. Regularization aims to prevent such over-fitting by adding constraints to the learning process. Much work is done on regularization of internal network properties and architectures. In this workshop we focus on regularization methods based on innate priors. There is strong evidence that an innate prior benefits deep nets: Adding convolution  to deep networks yields a convolutional deep neural network (CNN) which is hugely successful and has permeated the entire field. While convolution was initially applied on images, it is now generalized to graph networks, speech, language,  3D data, video, etc. Convolution models translation invariance in images: an object may occur anywhere in the image, and thus instead of learning parameters at each location in the image, convolution allows to only consider local relations, yet, share parameters over all image locations, and thus saving a huge number of parameters to learn, allowing a strong reduction in the number of examples to learn from. This workshop aims to further the great success of convolution, exploiting innate regularizing structures yielding a significant reduction of training data.

## Workshop program

Our live program featured a panel discussion with our [invited speakers](#invited-speakers), as well as playback of recorded talks for all presentations and live Q&A. All keynotes, papers and presentations were made available through the [ECCV Workshops and Tutorials website](https://workshopsandtutorials.eccv2020.eu/papers/subject/visual-inductive-priors-for-data-efficient-deep-learning/).

| Time (UTC+1) | | |
| -- | -- | -- |
| 8:00 / 18:00  | Keynote session     | Panel discussion with [invited speakers](#invited-speakers) + Q&A                         |
| 8:40 / 18:40   | *Break*        |                                                |
| 8:45 / 18:45  | Oral session | [Oral presentations](#oral-session)                             |
| 9:10 / 19:10 |              | Q&A                                            |
| 9:25 / 19:25 | Challenges           | [Awards & winners presentations](challenges)               |
| 9:35 / 19:35 | Poster session      | [Poster presentations](#poster-session)             |
| 9:45 / 19:45 |              | Q&A (for posters & challenges)              |
| 9:50 / 19:50 |              | [External poster presentations](#external-poster-session)                  |
| 9:55 / 19:55 | *Closing*      |                          |

### Oral session

1. Lightweight Action Recognition in Compressed Videos. <br />*Yuqi Huo, Xiaoli Xu, Yao Lu, Yulei Niu, Mingyu Ding, Zhiwu Lu, Tao Xiang, Ji-Rong Wen*
2. On sparse connectivity, adversarial robustness, and a novel model of the artificial neuron. <br />*Sergey Bochkanov*
3. Injecting Prior Knowledge into Image Caption Generation. <br />*Arushi Goel, Basura Fernando, Thanh-Son Nguyen, Hakan Bilen*
4. Learning Temporally Invariant and Localizable Features via Data Augmentation for Video Recognition. <br />*Taeoh Kim, Hyeongmin Lee, MyeongAh Cho, Hoseong Lee, Dong heon Cho, Sangyoun Lee*
5. Unsupervised Learning of Video Representations via Dense Trajectory Clustering. <br />*Pavel Tokmakov, Martial Hebert, Cordelia Schmid*

### Poster session

1. Distilling Visual Priors from Self-Supervised Learning. <br />*Bingchen Zhao, Xin Wen*
2. Unsupervised Image Classification for Deep Representation Learning. <br />*Weijie Chen, Shiliang Pu, Di Xie, Shicai Yang, Yilu Guo, Luojun Lin*
3. TDMPNet: Prototype Network with Recurrent Top-Down Modulation for Robust Object Classification under Partial Occlusion. <br />*Mingqing Xiao, Adam Kortylewski, Ruihai Wu, Siyuan Qiao, Wei Shen, Alan Yuille*
4. What leads to generalization of object proposals?. <br />*Rui Wang, Dhruv Mahajan, Vignesh Ramanathan*
5. A Self-Supervised Framework for Human Instance Segmentation. <br />*Yalong Jiang, Wenrui Ding, Hongguang Li, Hua Yang, Xu Wang*
6. Multiple interaction learning with question-type prior knowledge for constraining answer search space in visual question answering. <br />*Tuong Do, Binh Nguyen, Huy Tran, Erman Tjiputra, Quang Tran, Thanh Toan Do*
7. A visual inductive priors framework for data-efficient image classification. <br />*Pengfei Sun, Xuan Jin, Wei Su, Yuan He, Hui Xue', Quan Lu*

### External poster session

1. Select to Better Learn: Fast and Accurate Deep Learning using Data Selection from Nonlinear Manifolds. <br />*Mohsen Joneidi, Saeed Vahidian, Ashkan Esmaeili, Weijia Wang, Nazanin Rahnavard, Bill Lin, and Mubarak Shah*
2. Compositional Convolutional Neural Networks: A Deep Architecture with Innate Robustness to Partial Occlusion. <br />*Adam Kortylewski, Ju He, Qing Liu, Alan Yuille*
3. On Translation Invariance in CNNs: Convolutional Layers can Exploit Absolute Spatial Location. <br />*Osman Semih Kayhan, Jan C. van Gemert*

## VIPriors Challenges

We presented the "Visual Inductive Priors for Data-Efficient Computer Vision" challenges. We offered four challenges, where models are to be trained from scratch, and we reduced the number of training samples to a fraction of the full set.

Please see the [challenges page](/challenges) for the results of the challenges.

## Invited speakers

{% include feature_row id="speakers_row" %}

## Organizers

{% include feature_row id="organizers_row" %}

### Contact

Email us at vipriors-ewi AT tudelft DOT nl