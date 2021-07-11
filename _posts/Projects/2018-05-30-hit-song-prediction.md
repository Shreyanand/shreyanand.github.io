---
title: Hit song prediction
layout: default
tags: music, Machine Learning
categories: Projects
main_image: "/images/projects/music.png"
description: This is a sample project.
---

[**Project Github**](https://github.com/Shreyanand/Music_Hit_Prediction_-acoustic_data)

Music industry has been growing rapidly with the advent of subscription based streaming services such as Spotify, Amazon, Apple, and Google music. Your favourite music has never been so easily accessible. For the music makers out there, finding a stage and an audience that appreciates your work is now more easy than ever. In this project, we analyze a collection of songs and based on their rankings, train a model that predicts whether a song will be a hit or not.

In the first phase of the project, we collected data from two sources:
[Official charts](www.officialcharts.com) to get songs that are top ranked and those that are not
Spotify API that gives information about the songs that we used as features. For example, we had features such as _track_ , _danceability_, _energy_, _key_, _loudness_,  _mode_, _time-signature_ e.t.c.

In the next phase, we implemented data preprocessing steps such as imputation, normalization, deduplication, and feature selection. Then, we designed  a  machine  learning  pipeline  to plug in models  such  as  logistic  regression,  neural  network,  decision  trees,  and  adaboost to find the best combination with best performance (F-score). We achieved an 83% F-score with the final model which was a Random Forest Classifier. The project suggests that such an approach can be used for predicting the popularity of a new song. A cool thing for the future could be to evaluate the features contributing to high performance and recommend changes to song creators to improve their songs.

Overall, the project was successful and we presented a poster. I learnt how to design and structure experiments to find the best models and parameters for a machine learning problem. Fetching data from different sources to solve the problem involved multiple iterations and sanity checks. In our team of seven, we had several productive brainstorming sessions. From this experience, I learnt how to collaborate and deliver the results together as a team.
