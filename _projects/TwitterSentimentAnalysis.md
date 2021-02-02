---
title: "Twitter Sentiment Analysis"
collection: projects
type: " Individual Project"
permalink: /projects/TwitterSentimentAnalysis
venue: "Imperial College London, Department of Computing"
date: 2019-9-6
location: "London, UK"
---
Master Individual Project Supervised by Dr. Gopalan Anandha; <br>
Analyse the usage and emotional feature of Twitter with Machine Learning (ML) and Natural Language Processing (NLP);

Main Work
======

* Aiming at the extensive use of Emoji and emoticon in social media (twitter), NLP technology is used to analyse the emotion sentiment (positive, neutral and negative), and deployed a friendly web page as the application interface.

* Use manual automatic tagging based on VADER (a non-ML based approach) for crawled data. Focal Loss is used as the loss function to alleviate the data imbalance in the classification task to a certain extent. We design the deep learning network architecture based on BERT as the feature extractor, achieving 81% accuracy for plain text.

* Considering the semantic interaction between Emoji and plain text, attention weights are generated to capture the contextual semantic. A pre-training data set of Emoji is constructed to simulate the use of real scenes, which is used to feed the model to strengthen Emoji embedding, ensuring the relative balance between text and Emoji in the training process of the attached model, resulting in an accuracy of 87%.

Technology
======
* Language: Python, JavaScript, PHP
* Machine Learning and Natural Language Processing
* Attention and Transformers

Link
======
[Source Code](https://github.com/ZheyuYe/TwitterSA) <br>
[Report](../files/TwitterSentimentAnalysis_report.pdf) <br>
[Presentation](../files/TwitterSentimentAnalysis_presentation.pptx)
