---
title: 'Iwenbooks Development'
summary: Detail description about the iwen APP
tags:
  - Development
date: '2021-09-30T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: 'http://adapt.seiee.sjtu.edu.cn/iwen/'

image:
  caption: Screenshot of iwen APP
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

Iwen is a book and news reading APP, which currently provides service for more than 20,000 users. Many useful modules are implemented in this APP which help users to better understand the reading materials, for example, the TTS(text-to-speech), auto-translation, auto-question-generation and so on. 

Besides the role of CTO and team management. I mainly responsible for the back-end development, the database maintenance and the implementation of recommendation algorithm.

- Design the database structure for the news/user data and develop API for the front-end.
- Implement the vanilla book/news recommendation system, which is based on a hybrid strategy combining collaborative filtering and user portraits. For books, I consider content information like the abstract and timeliness of books in the users' history to model users' interests. For news, I summarize the topic that each user may be interested in and adjust the recommendation score personalizely for them in real time.