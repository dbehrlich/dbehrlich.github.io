---
layout: post
title: "Direct Feedback Alignment vs Backprop"
date: 2016-10-15
---

<div>

<h1>Direct Feedback Alignment</h1>

<h2>Feedback Alignment Methods</h2>

<p>Feedback Alignment proposes the use of random fixed weight matrices to propogate error through a neural network for the purpose of weight updates. Direct feedback alignment takes this concept further, and instead of propogating through each layers random weight matrix directly uses the product of the the error and a random weight matrix as a nearly local update rule.</p>

## Figures

![alt text](https://github.com/dbehrlich/dbehrlich.github.io/figures/DirectFeedbackAlignement_xor.png "Training Example")

![alt text](https://github.com/dbehrlich/dbehrlich.github.io/figures/DirectFeedbackAlignement_xor_1000.png "Training Example")

</div>


