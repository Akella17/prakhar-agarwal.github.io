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

### Voice Style Transfer
* Extending the work of Gatys et al.on neural artistic style transfer to audio signals.<br>
* Uses siamese network with triplet loss function.

### Disentangled Learning in β-Variatonal Auto-Encoders
* Baseline: Implementing the β-VAE paper of DeepMind to extract disentangled factors from dsprites dataset.<br>
* Balancing the trade-off between disentanglement and reconstruction fidelity by adjusting the hyperparameter β. <br>
* Disentanglement helps with zero-shot inference and faster knowledge transfer to new tasks.

### Face Recognition with One-Shot Learning
* Used one-shot learning to build a face recognition system.<br>
* Transfers selected speaker’s features like pitch and timbre across speech signals.

### Art Generation with Neural Style Transfer
* Implementation of Gatys et al. paper on neural style transfer.<br>
* Blends low level features of style image with high level features of context image.

### Trigger Word Detection
* Detects trigger words from continuous audio stream using LSTM.<br>
* Uses CTC cost for speech recognition.

### Debiasing Word Embeddings
* Word embeddings can often represent gender, ethnicity, age and other biases of the text used to train the model. Debiasing is performed on word embeddings to remove observed biases. Based on work byBolukbasi et al., 2016.

## Mentored Projects
<hr>

### Speaker Recognition using Neural Networks

*Machine Vision Laboratory, IIT Roorkee* \| January 2018 – May 2018<br>
<i>Supervisors: Dr. Ajit K Chaturvedi, Professor & Director, IIT Roorkee and Dr. R Balasubramanian, Associate Professor, IIT Roorkee</i><br>
* Trained a speaker recognition neural network using softmax classifier.<br>
* Trained a speaker embedding neural network using triplet loss funtion.<br>

### Motion Vector Encryption on MPEG Video Files

*Signal Processing Laboratory, IIT Roorkee* \| January 2017 – April 2017<br>
<i>Supervisor: Dr. Vinod Pankajakshan, Assistant Professor, IIT Roorkee</i><br>
* Extract and encrypt the motion vectors of an MPEG video file.<br>
* Our modified approach consists of shifting the present motion vectors based on the previously encrypted frame, providing greater immunity from random guessing attacks.<br>

### Enhanced MAC (Multiply and Accumulate) unit used in modern DSP Processors

*Embedded Systems Course Project* \| October 2016<br>
<i>Supervisor: Dr. Brajesh Kumar Kaushik, Associate Professor, IIT Roorkee</i><br>
* Designed an enhanced MAC unit with pipelined architecture to increase the throughput.<br>
