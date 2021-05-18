---
title: ":pill: Parkinson Monitoring"
layout: post
date: 2020-08-20 22:48
tag:
- parkinson-monitoring
- sensor
- time-series-classification
- multi-input-models
- hyperparameter-tuning
image: https://borhenryk.github.io/henryk_githubpage/assets/images/ts_class.png
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "Parkinson Monitoring from sensor Data"
category: project
author: henryk
externalLink: false
---

<p align="justify">Recent advances in mobile health have demonstrated great potential to leverage sensor-based technologies for quantitative, remote monitoring of health and disease - particularly for diseases affecting motor function such as Parkinson’s disease. While infrequent doctor’s visits along with patient recall can be subject to bias, remote monitoring offers the promise of a more objective, holistic picture of the symptoms and complications experienced by patients on a daily basis, which is critical for making decisions about treatment.</p>

<p align="justify">Previous work, including the 2017 Parkinson’s Disease Digital Biomarker DREAM Challenge, showed that Parkinson’s diagnosis and symptom severity can be predicted using wearable and consumer sensors worn during the completion of specific short tasks. The BEAT-PD Challenge sought to understand whether symptom severity could be predicted from passive monitoring of patients, as they went about their daily lives, which is a critical component to developing algorithms for remote monitoring. To this end, we leveraged two previously unavailable data sets which collected passive accelerometer data from wrist-worn devices coupled with patient self-reports of symptom severity. Participants were asked to build patient-specific models to predict on/off medication status (subchallenge 1), dyskinesia, an often-violent involuntary movement which arises as a side-effect of medication (subchallenge 2), and tremor (subchallenge 3) for 28 patients. The participant models were compared to a patient-specific null model.</p>

<p align="justify">Through this challenge, as well as the post-challenge community phase, we determined that sensor measurements from passive monitoring of Parkinson’s patients can be used to predict symptom severity for a subset of patients. Moreover, these models were also predictive for in-clinic physician-assessments of severity. Patient predictability was generally not related to factors like sample size or reporting lag but was somewhat related to overall disease severity.</p>
