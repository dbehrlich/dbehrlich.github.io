---
layout: post
title: "Hello World"
date: 2016-10-14
---

#Direct Feedback Alignment

##Feedback Alignment Methods

Feedback Alignment proposes the use of random fixed weight matrices to propogate error through a neural network for the purpose of weight updates. Direct feedback alignment takes this concept further, and instead of propogating through each layers random weight matrix directly uses the product of the the error and a random weight matrix as a nearly local update rule.

## Figures

![alt text](https://github.com/dbehrlich/dbehrlich.github.io/figures/DirectFeedbackAlignement_xor.png "Training Example")

![alt text](https://github.com/dbehrlich/dbehrlich.github.io/figures/DirectFeedbackAlignement_xor_1000.png "Training Example")


