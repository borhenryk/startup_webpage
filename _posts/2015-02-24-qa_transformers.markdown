---
title: ":eyes: Question-answering with Transformers"
layout: post
date: 2020-08-20 22:48
tag:
- question-answering
- transformers
- language-models
- nlp
image: https://borhenryk.github.io/henryk_githubpage/assets/images/transformers.png
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "Custom QA language model"
category: project
author: henryk
externalLink: false
---


<p align="justify">Recent advances in large language models such as BERT, RoBERTa, ALBERT etc. changed the field of information extraction from unstructured data (using QA). Nevertheless, due to the huge amount of annotated data (Stanford Question answering dataset for Question Answering tasks), most progress has been made in English. A translation of the SQuAD dataset would make it possible to achieve better results for this type of task in other languages where this type of data is limited or not available at all.</p>

<div class="side-by-side">
    <div class="toleft">
        <img class="image" src="https://borhenryk.github.io/henryk_githubpage/assets/images/downloads_huggingface.png" alt="Alt Text">
        <figcaption class="caption">Downloads of the Dutch QA model (14.09.2020)</figcaption>
    </div>

    <div class="toright">
        <p align="justify">Huggingface allows you to train your own language models and adapt them to specific downstream tasks such as Q&A, classification, text summary, etc. and then share them with the community. I have provided 4 models for Polish and Dutch Q&A tasks (for SQuAD v1.0 and v2.0). You can also find benchmarks in the respective model cards on the huggingface page.</p>
    </div>
</div>


Helpful links:
* [The page to Huggingface](https://huggingface.co/)
* [GitHub Repo for SQuAD translation](https://github.com/borhenryk/train_custom_qa_model)
* [Deepset Q&A annotation tool](https://annotate.deepset.ai/)