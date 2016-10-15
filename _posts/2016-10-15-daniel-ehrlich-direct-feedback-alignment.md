---
layout: post
title: "Direct Feedback Alignment vs Backprop"
date: 2016-10-15
---

<div>

<h2>Feedback Alignment Methods</h2>

<p>Feedback Alignment proposes the use of random fixed weight matrices to propogate error through a neural network for the purpose of weight updates. Direct feedback alignment (DFA) takes this concept further, and instead propogates the error directly through a single random weight matrix to its respective layer. As such it consitutes a nearly local update rule. The purpose of this post is to explain the DFA update rule as well as compare its performance against traditional backprop. </p>

<h2>Results</h2>

</div>

![Fig 1](https://github.com/dbehrlich/dbehrlich.github.io/blob/master/figures/DirectFeedbackAlignement_xor.png?raw=true)

![Fig 2](https://github.com/dbehrlich/dbehrlich.github.io/blob/master/figures/DirectFeedbackAlignement_xor_1000.png?raw=true)







