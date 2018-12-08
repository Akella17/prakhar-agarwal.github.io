---
layout: archive
permalink: /projects/
title: ""
date: 2014-06-02T15:05:16-04:00
modified: 2016-01-04T16:38:17-05:00
excerpt: 
ads: false
fullwidth: true
tiles: true
feature:
  visible: false
  headline: "Featured Work"
  category: project
---

{{ page.excerpt | markdownify }}

## Self-Supervised Projects
<hr>

### Handwriting Synthesis
* Mixture distribution parameterized using an LSTM network (Mixture Density Network) to generate realistic
cursive handwriting, demonstrating the ability of recurrent neural networks to capture long-range structure.

### Language Identification
* Character-level LSTM model for language identification based on Stanford Language Identification Engine(SLIDE).

### Disentangled Learning in β-Variatonal Auto-Encoders
* { Balanced the trade-off between learning disentangled representations and reconstruction fidelity by adjusting the
hyperparameter β to extract disentangled factors from dsprites dataset. <br>
* Achieved more robust disentangling at a higher reconstruction fidelity using the modified objective function that
performs a controlled increase of encoding capacity.

### Face Recognition with One-Shot Learning
*  Used a siamese network with triplet loss function to recognize faces from a single example.

### Art Generation with Neural Style Transfer
* Generated artwork of high perceptual quality by blending low-level features and high-level features of two images.

### Trigger Word Detection
* Used a stacked LSTM network to detect trigger words from a continuous audio stream.

### Debiasing Word Embeddings
* Eliminated common biases in word embeddings such as gender, age, etc., emerging from unbalanced training sets.

## Mentored Projects
<hr>

### Speaker Recognition using Neural Networks

*Machine Vision Laboratory, IIT Roorkee* \| January 2018 – May 2018<br>
<i>Supervisors: Dr. Ajit K Chaturvedi, Professor & Director, IIT Roorkee and Dr. R Balasubramanian, Associate Professor, IIT Roorkee</i><br>
* Reviewed common feature extractors used in pre-processing raw audio signals for speaker recognition task.<br>
* Experiments were performed with stacked LSTM architecture using the Voice Conversion (VCC) 2016 dataset.<br>
* Compared the performance of convolutional auto-regressive networks (dilated causal convolutions with a finite
receptive field) with stacked LSTM networks (theoretically infinite receptive field) for high fidelity speech synthesis
and automatic speech recognition tasks.

### Motion Vector Encryption on MPEG Video Files

*Signal Processing Laboratory, IIT Roorkee* \| January 2017 – April 2017<br>
<i>Supervisor: Dr. Vinod Pankajakshan, Assistant Professor, IIT Roorkee</i><br>
* Extract and encrypt the motion vectors of an MPEG video file.<br>
* Our modified approach consists of shifting the present motion vectors based on the previously encrypted frame, providing greater immunity from random guessing attacks.<br>

### Enhanced MAC (Multiply and Accumulate) unit used in modern DSP Processors

*Embedded Systems Course Project* \| October 2016<br>
<i>Supervisor: Dr. Brajesh Kumar Kaushik, Associate Professor, IIT Roorkee</i><br>
* Designed an enhanced MAC unit with pipelined architecture to increase the throughput.<br>
