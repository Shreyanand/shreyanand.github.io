---
title: Story generator
layout: default
tags: RNN, sentence to vector, NLP
categories: Projects
main_image: "/images/projects/story_main.png"
description: Stories are exciting and we are naturally wired to process and generate them. Can we train a model that interacts with users to generate very simple stories?
---

[**Project Github**](https://github.com/Shreyanand/story_generator)

Stories are the basis of human conversations. From young kids to leaders with high stakes, everyone loves well formed stories. With constant efforts of making computers understand human languages, or atleast mimic them,  processing and generating stories is an interesting and challenging problem. In this project, we trained a model that interacts with users to generate very simple five sentences long stories.


The dataset we used for this problem was  ROCStories which is a collection of 50k five sentence long stories. For a better learning, we pre-processed the stories to find named entities and replace them with one name “John” and replaced pronominal references like “he” using coreference resolution. Then, we trained a Gated Recurrent Unit model using pytorch library to predict the next sentence. Given the story so far, which can be a mixture of human generated and model selected sentences, the model predicts and suggests the next sentence.  Following is an example story generated using the model:

![story_framework.png]({{"/images/projects/story_generator.png" | absolute_url }})

In hindsight, this may not seem like a lot, but anyone who studied language understanding pre  BERT, GPT, and transformer based models era, knows that it was hard work. This was my first hands-on applied deep learning project, frustrating at times, but eventually a rewarding experience.

Did you know? If you keep your laptop in the backpack, with a learning mode running, it may get fried.
