---
title: ":black_nib: Text generation for financial reports"
layout: post
date: 2020-08-20 22:48
tag:
- text-generation
- deep-learning
- lstm
- gru
image:  <img src="https://borhenryk.github.io/henryk_githubpage/assets/images/text_generation_sampling.png" width="200" height="200">
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "Text generation with RNN's (LSTM, GRU cells)"
category: project
author: henryk
externalLink: false
---


The [master thesis](https://epub.ub.uni-muenchen.de/60631/) gives an insight into the theory and application of different methods of text generation. Since many areas of the economy are related to text-based problems, this thesis, in order to learn the financial language, used a data source of the financial statements of more than 5000 companies. With the help of different algorithms based on neural networks, an attempt was made to automatically generate text based on a given topic. This automation of recurring and repeatable tasks could save time and avoid human error in many situations. The master thesis is mainly addressed to people with a strong background in statistical and mathematical methods. The theory and practical application of Deep Learning is not a prerequisite, as the basic concepts are described extensively in the thesis.

<div class="side-by-side">
    <div class="toleft">
        <img class="image" src="https://borhenryk.github.io/henryk_githubpage/assets/images/LSTM_Ar.png" alt="Alt Text">
        <figcaption class="caption">LSTM Network Architecture</figcaption>
    </div>

    <div class="toright">
        <p>Since I had some problems to combine the information from the different sources I created the graphic to the left which shows a combination of the <a href="http://colah.github.io/posts/2015-08-Understanding-LSTMs/">blog post</a> and the <a href="https://jasdeep06.github.io/posts/Understanding-LSTM-in-Tensorflow-MNIST/">post here</a> where I think the graphics are very helpful but an error in explaining the number_units is present. Check the <a href="https://stackoverflow.com/questions/37901047/what-is-num-units-in-tensorflow-basiclstmcell/53760729#53760729">Stack Overflow Answer</a> for detailed information and the full size graphic.</p>
    </div>
</div>
