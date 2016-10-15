---
layout: post
title: "Direct Feedback Alignment vs Backprop"
date: 2016-10-15
---

<div>

<h3>Feedback Alignment Methods</h3>

<p>Feedback Alignment proposes the use of random fixed weight matrices to propagate error back through a neural network during training. Direct feedback alignment (DFA) takes this concept further, and instead transfers the error directly through a single random weight matrix to its respective layer. As such it consitutes a nearly local update rule. The purpose of this post is to explain the DFA update rule(coming soon) as well as compare its performance against traditional backprop. </p>

<h3>Results</h3>

<p>I trained two feedforward neural networks with the same intialization to perform the xor operation. The first was trained using the direct feedback alignment algorithm, and the second was trained using backprop. Results from a single training example are presented below.</p>

<img src="/figures/DirectFeedbackAlignement_xor.png" alt="samples" style="width: 800px;"/>

<p>Interestingly the convergence pattern demonstrated above was not idiosyncratic to that initialization. Over the average of 1000 trainings it is clear that while backpropagation begins to learn faster, direct feedback alignment quickly catches up and converges more quickly to a lower error solution.</p>

<img src="/figures/DirectFeedbackAlignement_xor_1000.png" alt="samples" style="width: 800px;"/>


<h3>Code</h3>

<p>Code used to generate this post available at my github account: <a href="https://github.com/dbehrlich/directFeedbackAlignment">github.com/dbehrlich</a></p>


<h3>References</h3>

<p>Nøkland, Arild. "Direct Feedback Alignment Provides Learning in Deep Neural Networks." arXiv preprint arXiv:1609.01596 (2016).</p>

</div>








