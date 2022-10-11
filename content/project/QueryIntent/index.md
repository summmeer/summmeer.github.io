---
title: 'Postweb Query Intention Detection Model'
summary: Detail description about the internship in Microsoft STCA
tags:
  - Deep Learning
  - Information Retrival
  - Search Engine
date: '2022-05-30T00:00:00Z'

# Optional external URL for project (replaces project detail page).
# external_link: 'https://xxx'

image:
  caption: The workflow of query intention detection framework
  focal_point: Smart

links:
  # - icon: twitter
  #   icon_pack: fab
  #   name: Follow
  #   url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

In order to optimize the search result, it is necessary to judge whether the intents of different search Query1 and Query2 are consistent, which is formulated as a binary classification task. Based on the cross-language pre-training model InfoXLM, I train the downstream binary classification task, that is, cross-language Query intent detection, and introduce PostWeb information (ie, text information such as the title, link, and abstract of the Query search result) as an additional feature of the Query. The classification model increases the AUC by about 1% on the test data set while achieving around 5% improvement on the financial stock test data set.

First I mined the training/test data from Bing Search Log and Scraper, to fetch the `title`, `URL` and `snippet` as additional features. Then I built the training pipeline, and train the post-web QQ model. Then, I evaluate the performance of the post-web model on different languages, which shows the improvement is more apparent in minor languages such as ja, ko, zh. When fixing the precision of the model at 98%, the number of recalled items (using post-web model) is more than 10% of the pre-web model. 

Second, I did some work on the model attention layer visualization, using two python package `bertviz` and `lit`, then did the case study. By analysis of bad cases (the bad case is a case that the pre-web model predict correctly while the post web not), I have some observations: 

- sometimes the model cannot catch the attention relation between similar words; 
- too many snippet words make the model confused; 
- the post web information (search result) is not accurate; 
- need to improve the quality of labeling. 