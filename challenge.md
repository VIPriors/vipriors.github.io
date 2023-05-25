---
layout: single
title: "<span class='header-marking'>Challenges</span>"
header:
  overlay_image: assets/images/logo_challenge_header.png
classes: semiwide
permalink: /challenges/
toc: false
---

<!-- <img src='/assets/images/logo_challenge.png' style='display: block; margin: 0 auto; width: 40%; min-width: 200px;' /> -->

We present the **"Visual Inductive Priors for Data-Efficient Computer Vision"** challenges. We offer two challenges, where models are to be trained from scratch in a data-deficient setting:

2. Object detection
3. Instance segmentation

These tasks were chosen to encourage researchers of arbitrary background to participate: no giant GPU clusters are needed, nor will training for a long time yield much improvement over the baseline results.

In addition to an award for the top submission by performance, this year will see the introduction of an additional jury-based prize for the most interesting submission.

## Synergy Sports

[<img src='/assets/images/SynergySportsLogo.png' style='display: block; float: right; width: 30%; min-width: 150px;' />](https://synergysports.com/)

Our VIPriors challenges are co-organized by **Synergy Sports**. The instance segmentation task is powered by their data, and they are lending their support in organizing the challenges.

Synergy Sports is changing how sport is organised, played, coached, commercialized, and experienced around the world. We help federations, leagues, clubs, coaches, referees, and players increase their performance on and off the field. Synergy Sports operates in 41 countries. In the US, Synergy serves every single NBA, G League, WNBA, and NCAA Division I basketball team, as well as every MLB team and over 270 NCAA Division I baseball teams. Visit [their website](https://synergysports.com/) for more information.


## Important dates

- Challenges open: June 1st, 2023;
- Challenges close: September 1st, 2023;
- Technical reports due: September 11th, 2023;
- Winners announced: Live session @ ICCV.

## Rules

- We prohibit the use of other data than the provided training data, i.e., **no pre-training**, no transfer learning.
- For submissions on CodaLab to qualify to the challenge we require the authors submit either a **technical report** or a full paper about their final submission. See details below under "Report". Submissions without a report or paper associated do not qualify to the competition.
- Top contenders in the challenge may be required to submit their submissions to peer review to ensure reproducability and that the rules of the challenge were followed. The organizers will contact contenders for this when necessary after the challenges close.
- Organizers retain the right to disqualify any submissions that violate these rules.

## Report

For the submission on CodaLab to qualify for the competition, we require the authors to submit a technical report of at least three pages about the submission. The deadline for these reports is September 9th. Authors are to submit their report to ArXiv and submit the link to vipriors-ewi AT tudelft DOT nl. Those unable to submit to Arxiv can email their report directly to vipriors-ewi AT tudelft DOT nl. After the conference we will publish the links to the technical reports on the workshop website.

## Submission

Both challenges are hosted on CodaLab, a public platform for AI challenges. Submissions must be made by uploading files containing predictions according to the format defined in the toolkit (see *Resources* for details) to the challenge pages listed below.

Please find the challenges here:

- [Object detection](https://codalab.lisn.upsaclay.fr/competitions/13493)
- [Instance segmentation](https://codalab.lisn.upsaclay.fr/competitions/13494)

## Resources

To accommodate submissions to the challenges we provide a toolkit that contains

- Python tools for generating the appropriate training and validation data;
- documentation of the required submission format for the challenges;
- implementations of the baseline models for each challenge.

See [the GitHub repository of the toolkit here](https://github.com/VIPriors/vipriors-challenges-toolkit).

## Questions

If you have any questions, please first check the Frequently Asked Questions in [the toolkit repository](https://github.com/VIPriors/vipriors-challenges-toolkit). If your question persists, you can ask it on the forums of the specific challenge on the CodaLab website. If you need to ask us a question in private, you can email us at vipriors-ewi AT tudelft DOT nl.
