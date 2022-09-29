#  Music Separation Enhancement With Generative Modeling

This is the official implementation of the Make it Sound Good (MSG) model from our 2022 ISMIR paper "Music Separation Enhancement with Generative Modeling" [\[paper\]](https://arxiv.org/pdf/2208.12387.pdf)[ \[website\]](https://interactiveaudiolab.github.io/project/msg.html)

We introduce Make it Sound Good (MSG), a post-processor that enhances the output quality of source separation systems like Demucs, Wavenet, Spleeter, and OpenUnmix
![](https://interactiveaudiolab.github.io/assets/images/projects/MSG-hero-image.png)

## Table of Contents
- [Setup](#Setup)
- [Training](#Training)
- [Inference](#Inference)
- [Citation](#Citation)

## Setup
1. We train our model using salient source samples from the training data. To get the salient source samples, our training loop uses [nussl's](https://github.com/nussl/nussl/tree/salient_mixsrc2/nussl) SalientExcerptMixSourceFolder class from the salient_mixsrc2 branch. The specific branch of the repo can be downloaded using the steps below:
```
$ git clone https://github.com/nussl/nussl.git
$ cd nussl
$ git checkout salient_mix_src
$ pip install -e .
```
2. Download our repo from github.
```
$ pip install https://github.com/interactiveaudiolab/MSG.git
```
3. Download the requirements.txt.
```
$ pip install -r requirements.txt
```

## Training

## Inference

## Citation
