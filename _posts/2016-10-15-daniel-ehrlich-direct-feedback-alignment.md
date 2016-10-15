---
layout: post
title: "Direct Feedback Alignment vs Backprop"
date: 2016-10-15
---

<div>

<h2>Feedback Alignment Methods</h2>

<p>Feedback Alignment proposes the use of random fixed weight matrices to propogate error through a neural network for the purpose of weight updates. Direct feedback alignment (DFA) takes this concept further, and instead propogates the error directly through a single random weight matrix to its respective layer. As such it consitutes a nearly local update rule. The purpose of this post is to explain the DFA update rule as well as compare its performance against traditional backprop. </p>

<h2>Results</h2>

<img src="/figures/DirectFeedbackAlignement_xor.png" alt="samples" style="width: 200px;"/>

</div>

![Fig 1](/figures/DirectFeedbackAlignement_xor.png )

![Fig 2](/figures/DirectFeedbackAlignement_xor_1000.png?raw=true)







