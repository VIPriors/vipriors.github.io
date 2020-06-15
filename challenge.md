---
layout: single
title: Challenges
classes: semiwide
permalink: /challenges/
toc: true
---

<img src='/assets/images/logo_challenge.png' style='display: block; margin: 0 auto; width: 40%; min-width: 200px;' />

We present the **"Visual Inductive Priors for Data-Efficient Computer Vision"** challenges. We offer four challenges, where models are to be trained from scratch, and we reduce the number of training samples to a fraction of the full set. The winners of each challenge are invited to present their winning method at the VIPriors workshop presentation at ECCV 2020. The four data-deficient challenges are:

1. [Image classification](https://competitions.codalab.org/competitions/23713) on [ImageNet](http://www.image-net.org/)
2. [Semantic segmentation](https://competitions.codalab.org/competitions/23712) on [Cityscapes](https://www.cityscapes-dataset.com/)
3. [Object detection](https://competitions.codalab.org/competitions/23661) on [MS COCO](http://cocodataset.org/#home)
4. [Action recognition](https://competitions.codalab.org/competitions/23706) on [UFC-101](https://www.crcv.ucf.edu/data/UCF101.php)

These tasks were chosen to encourage researchers of arbitrary background to participate: no giant GPU clusters are needed, nor will training for a long time yield much improvement over the baseline results.

## Important dates

- Challenges open: March 11, 2020
- Challenges close: July 10, 2020
- Technical reports due: July 17, 2020
- Winners announced: July 24, 2020

## Data

As training data for these challenges we use subsets of publicly available datasets. We do not directly provide the data but instead expose tooling to generate the subsets from the canonical versions of the publicly available full datasets through our toolkit. Please refer to *Resources* for details.

## Rules

- We prohibit the use of other data than the provided training data, i.e., **no pre-training**, no transfer learning.
- For submissions on CodaLab to qualify to the challenge we require the authors submit either a **technical report** or a full paper about their final submission. See details below under "Report". Submissions without a report or paper associated do not qualify to the competition.
- Top contenders in the challenge may be required to submit their submissions to peer review to ensure reproducability and that the rules of the challenge were followed. The organizers will contact contenders for this when necessary after the challenges close.
- Organizers retain the right to disqualify any submissions that violate these rules.
- The winners of each of the four challenges will get an **opportunity to present** their method at the VIPriors workshop at ECCV 2020. The organizers will contact contenders that are eligible for this opportunity after the challenges close.

## Report

For the submission on CodaLab to qualify for the competition, we require the authors to submit a technical report of at least three pages about the submission. The deadline for these reports is July 17th, the same date as the workshop paper deadline. Authors are to submit their report to ArXiv and submit the link to us using the form linked below. Please use the same format as for the paper track. After the conference we will publish the links to the technical reports on the workshop website.

Authors that are already submitting a paper about the submission to the workshop paper track are not required to submit a technical report. Instead, they are to use the same submission form to refer the challenge organizers to their submitted paper.

Link to submission form: [Google Form](https://docs.google.com/forms/d/e/1FAIpQLSdzTQXw60TL70hxDW1WsEp52AUI2CVe3QX7T0Qi420Gey9H9Q/viewform?usp=sf_link).

## Submission

Each of the four challenges are hosted on CodaLab, a public platform for AI challenges. Submissions must be made by uploading files containing predictions according to the format defined in the toolkit (see *Resources* for details) to the challenge pages listed below.

Please find the challenges here:

- [Image classification](https://competitions.codalab.org/competitions/23713)
- [Semantic segmentation](https://competitions.codalab.org/competitions/23712)
- [Object detection](https://competitions.codalab.org/competitions/23661)
- [Action recognition](https://competitions.codalab.org/competitions/23706)

## Resources

To accommodate submissions to the challenges we provide a toolkit that contains

- Python tools for generating the appropriate training and validation data;
- documentation of the required submission format for the challenges;
- implementations of the baseline models for each challenge.

See [the GitHub repository of the toolkit here](https://github.com/VIPriors/vipriors-challenges-toolkit).

## Questions

If you have any questions, please first check the Frequently Asked Questions in [the toolkit repository](https://github.com/VIPriors/vipriors-challenges-toolkit). If your question persists, you can ask it on the forums of the specific challenge on the CodaLab website. If you need to ask us a question in private, you can email us at vipriors-ewi AT tudelft DOT nl.

## Leaderboards

### Image Classification

<iframe src="https://competitions.codalab.org/competitions/leaderboard_widget/23713/" class='leaderboard' style="height: 500px; width: 100%; border: none;"></iframe>

### Semantic Segmentation

<iframe src="https://competitions.codalab.org/competitions/leaderboard_widget/23712/" class='leaderboard' style="height: 500px; width: 100%; border: none;"></iframe>

### Object Detection

<iframe src="https://competitions.codalab.org/competitions/leaderboard_widget/23661/" class='leaderboard' style="height: 500px; border: none;"></iframe>

### Action Recognition

<iframe src="https://competitions.codalab.org/competitions/leaderboard_widget/23706/" class='leaderboard' style="height: 500px; width: 100%; border: none;"></iframe>