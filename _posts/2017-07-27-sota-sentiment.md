---
layout: archive
title: "State-of-the-art in Sentiment Analysis"
date: 2017-07-27
---

### **What is State-of-the-art in Sentiment Analysis?**
---

State-of-the-art is a tricky concept. In sentiment analysis, which approach
works best often depends on the data you have at hand, whether your interested
in knowing the general sentiment of a document (document-level sentiment analysis)
or if you want to know what the sentiment is of a specific target entity 
(aspect-level sentiment analysis).

Another obstacle is that we often don't have the time or energy to devote 
to reimplementing others' approaches and rely on the results they present
in their papers. 

### **Results**
---

The first major surprise is that the old bag-of-words approach works amazingly
well across datasets. In fact, it comes very close to the best performing algorithms
on almost all of the datasets, as you can see in the next table.

<img src="../assets/images/bow.png" alt="Drawing" style="width: 600px;"/>


Rather unsurprisingly given their performance on so many tasks these days, bidirectional LSTMs are
the big winners.

<img src="../assets/images/bilstm-overall.png" alt="Drawing" style="width: 600px;"/>
