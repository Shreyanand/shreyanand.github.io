---
title: User reviews analysis
layout: default
tags: NLP, topic modelling
categories: Projects
main_image: "/images/projects/PCAvis.png"
description: How can we derive insights from a large volume of user reviews and feedback? Improve products and services through an automated analysis of reviews.
---

[**Project Github**](https://github.com/Shreyanand/Analysis_Mobile_Application_Comments)

User reviews and feedback is critical for the success of any product or service. With internet services like Amazon, Yelp, Youtube, Appstores, e.t.c it has become convenient for customers to review the products and services they consume.  A manual analysis of these reviews becomes challenging as  the product grows and the reviews scale. Interesting problems can be defined when you have a large dataset of user reviews for your product over time.  One of the relevant questions in this domain is how to automatically discover aspects (topics) and sentiments from the reviews.

For this project, I analyzed the reviews of users for various Iphone apps on the Apple applications’ store. I experimented with language models like Doc2vec for encoding the reviews and clustering them.  For finding topics, I applied the Latent Dirichlet Allocation approach and its variants on the data. I tried studying and implementing several approaches in the literature  such as unified models of aspect and sentiment detection from the reviews. The analysis, through interactive plots, demonstrated how we can apply topic modelling on the reviews dataset.

This project was one of my first few attempts at understanding and manipulating natural language data. I learnt how to clean and preprocess the reviews and then apply unsupervised learning algorithms to get insights from the data. As people do not always follow grammatical rules while writing reviews, I realized the problem is quite hard if you dig deeper. The complexity of making computers understand natural language, invited me to explore other avenues in Natural Language Processing.
