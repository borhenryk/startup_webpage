---
title: ":chart_with_upwards_trend: Unsupervised Anomaly Detection"
layout: post
date: 2020-08-20 22:48
tag:
- anomaly-detection
- unsupervised
- iforest
- lof
- excess-mass-curves
image: https://borhenryk.github.io/henryk_githubpage/assets/images/iForest_Color_Scala-1.png
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "Unsupervised Anomaly Detection for Log Data"
category: project
author: henryk
externalLink: false
---

<p>The aim of the project was to develop a more precise method using anomaly detection,
which evaluates these loading processes on the basis of the log files and provides information on possible errors
gives. In the choice of methods, the focus was on the broadest possible applicability
for the future, so that even higher dimensional data sets can be processed.
A particular challenge here was the evaluation of the methods used at the
Base of unlabeled data. For this purpose we use an approach that has been developing since 2015
and on the basis of Excess-Mass and Mass-Volume curves statements about the quality of
scoring functions meets.</p>

<p>The project showed that the methods iForest and Local Outlier Factor are suitable for to detect anomalies or to investigate observations. A suitable criterion for the evaluation of the methods and for the determination of the parameter values was the Excess-Mass-Volume criterion. These allow a Comparison between methods and can also handle unlabeled data.</p>

<div class="side-by-side">
    <div class="toleft">
        <img class="image" src="https://borhenryk.github.io/henryk_githubpage/assets/images/IForest.png" alt="Alt Text">
        <figcaption class="caption">LSTM Network Architecture</figcaption>
    </div>

    <div class="toright">
        <p></p>
    </div>
</div>


<iframe src="https://github.com/borhenryk/unsupervised_anomaly_detection/blob/master/18-04-11_Anomaly%20Detection_Vortrag.pdf" width="560" height="310" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe>
