---
layout: post
title: "Direct Feedback Alignment vs Backprop"
date: 2016-10-15
---

<div>

<h3>Feedback Alignment Methods</h3>

<p>Feedback Alignment proposes the use of random fixed weight matrices to propogate error through a neural network for the purpose of weight updates. Direct feedback alignment (DFA) takes this concept further, and instead propogates the error directly through a single random weight matrix to its respective layer. As such it consitutes a nearly local update rule. The purpose of this post is to explain the DFA update rule as well as compare its performance against traditional backprop. </p>

<h3>Results</h3>

<p>I trained a feedforward neural network with two hidden layers to perform the xor operation. I used the same initialization to train both using the direct feedback alignment algorithm as well as backprop. Results from a single training examples are presented below</p>

<img src="/figures/DirectFeedbackAlignement_xor.png" alt="samples" style="width: 800px;"/>

<p>Interestingly the convergence pattern demonstrated above was not idiosyncratic to that initialization. Over the average of 1000 trainings it is clear the while backpropagation begins to converge faster, direct feedback alignment quickly catches up and actually finds a superior solution.</p>

<img src="/figures/DirectFeedbackAlignement_xor_1000.png" alt="samples" style="width: 800px;"/>

</div>








