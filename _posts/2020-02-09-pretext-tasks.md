---
layout: post
title: Notes on Self-Supervision for Domain Generalization
date: 2021-02-02
author: aahlad
categories: ml
permalink: blog/pretexts.html
published: false
---

Notes from this paper: [Improving out-of-distribution generalization via multi-task self-supervised pretraining](https://arxiv.org/pdf/2003.13525.pdf)

## What is a pretext task? Why?

A task defined based on a known transformation of the covariates which does no require human annotation. Pretext tasks help with learning certain aspects of the objects in an image; detecting the rotation angle of a dog image requires some understanding of what a dog is.


> TL;DR : build a feature extractor (or representation) with multi-task SSL.

Few shot learning aims to replicate the human quality being able to classify based a small number of examples to a model. Humans do this due to the amazing visual cortex that is able to differentiate between complex shapes by quickly breaking them down into simple ones; humans do not start from scratch (quote by Chelsea Finn [here](https://www.youtube.com/watch?v=Rq40Bze_hMA&list=PLdDZb3TwJPZ4Ri6i0MIdesIEpYK4lx17Q&index=8)). How do we build such abilities (like breaking down into simple shapes) into a model?

Few-shot learning says hello.

Formally, (following from [this](https://dl.acm.org/doi/pdf/10.1145/3386252).)

## Why does this work for domain generalization?

While the label may suffer from a spurious correlation, individual features that come together in different ways to form different objects may not.
TODO: good example?
TODO: what about shortcuts? 

## Why might this not work for domain generalization?
If the extracted features are a bijective transformation of the input data, there cannot be statistical guarantees on learning from the features because the spurious dependence is preserved.

However, as the low-level features are now detected in different parts of the dimension, the representation may form well-separated clusters based on object differences which may lead to gradient descent preferring the non-spurious solution.

TODO: what about shortcuts?