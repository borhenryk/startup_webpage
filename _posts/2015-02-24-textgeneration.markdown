---
title: ":black_nib: Text generation for financial reports"
layout: post
date: 2020-08-20 22:48
tag:
- text-generation
- deep-learning
- lstm
- gru
image: https://sergiokopplin.github.io/indigo/assets/images/jekyll-logo-light-solid.png
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "Text generation with RNN's (LSTM, GRU cells)"
category: project
author: henryk
externalLink: false
---

## Summary:


<p>The (master thesis)[https://epub.ub.uni-muenchen.de/60631/] gives an insight into the theory and application of different methods of text generation. Since many areas of the economy are related to text-based problems, this thesis, in order to learn the financial language, used a data source of the financial statements of more than 5000 companies. With the help of different algorithms based on neural networks, an attempt was made to automatically generate text based on a given topic. This automation of recurring and repeatable tasks could save time and avoid human error in many situations. The master thesis is mainly addressed to people with a strong background in statistical and mathematical methods. The theory and practical application of Deep Learning is not a prerequisite, as the basic concepts are described extensively in the thesis.</p>

<div class="side-by-side">
    <div class="toleft">
        <img class="image" src="https://borhenryk.github.io/henryk_githubpage/assets/images/LSTM_Ar.png" alt="Alt Text">
        <figcaption class="caption">Photo by John Doe</figcaption>
    </div>

    <div class="toright">
        <p>Check out the Linked (master thesis)[https://epub.ub.uni-muenchen.de/60631/] or my (StackOverflow Answer)[https://stackoverflow.com/questions/37901047/what-is-num-units-in-tensorflow-basiclstmcell/53760729#53760729] for more details. Since you are mostly dealing with data that is very extensive, it is not possible to incorporate everything in one piece into the model. Therefore, data is divided into small pieces as batches, which are processed one after the other until the batch containing the last part is read in. In the lower part of the figure you can see the input (dark grey) where the batches are read in one after the other from batch 1 to batch batch_size. The cells LSTM cell 1 to LSTM cell time_step above represent the described cells of the LSTM model (http://colah.github.io/posts/2015-08-Understanding-LSTMs/). The number of cells is equal to the number of fixed time steps. For example, if you take a text sequence with a total of 150 characters, you could divide it into 3 (batch_size) and have a sequence of length 50 per batch (number of time_steps and thus of LSTM cells). If you then encoded each character one-hot, each element (dark gray boxes of the input) would represent a vector that would have the length of the vocabulary (number of features). These vectors would flow into the neuronal networks (green elements in the cells) in the respective cells and would change their dimension to the length of the number of hidden units (number_units). So the input has the dimension (batch_size x time_step x features). The Long Time Memory (Cell State) and Short Time Memory (Hidden State) have the same dimensions (batch_size x number_units). The light gray blocks that arise from the cells have a different dimension because the transformations in the neural networks (green elements) took place with the help of the hidden units (batch_size x time_step x number_units). The output can be returned from any cell but mostly only the information from the last block (black border) is relevant (not in all problems) because it contains all information from the previous time steps.</p>
    </div>
</div>
