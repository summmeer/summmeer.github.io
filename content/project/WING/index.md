---
title: 'A Search Engine from scratch based on the WikiPedia data'
summary: We build a Wikipedia-based search engine, with 5 sort algorithms, a well-designed GUI, and the responsive time scale of millisecond.
tags:
  - Development
  - Search Engine
date: '2021-05-30T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: 'https://github.com/summmeer/Search-Engine-based-on-Wiki-data'

image:
  caption: The overflow of WING
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

Wikipedia is a well-known free online encyclopedia, created and edited by volunteers around the world, and it offers free copies of all available content, where we can get the latest complete dump of the English-language Wikipedia. Thus, we build a Wikipedia-based search engine: Wing, with 5 sort algorithms, a well-designed GUI, and the responsive time scale of millisecond. Wing is short for ``Wing Is Not Google''.

After we download the 17GB zip file of the whole raw data and unzip it, we use a Wiki-Extractor tool to extract around 10 million documents. We use SPIMI (Single-Pass In-Memory Indexing) algorithm to construct posting list. 

### Algorithm Optimize
TF-IDF based methods will give short articles high weights. So, there will be a problem that some docs that their content is very short but not very relative to the query, have high weights in ranking results. Thus, when we calculate the term frequency, we increase the term frequency of the words that appear in the title. Through this way, we can filter some short but meaning less docs and get what we want.

We optimized TF-IDF with PageRank score, which is computed to measure the authority of pages.

### Developemnt
We adopt Flask to enable our back end. Flask is a microframework for web appliction written in Python. Front end is implemented with Vue. Vue is a progressive framework for building user interfaces. Also, we use Element UI, a desktop component library, to make our interface more beautiful and user-friendly. Front end includes three pages: welcome page, query page, and article page. It is well known that Python program is running as a single process and is very slow. To speed up our program written by Python, we use Multiprocess package to accelerate our for-loop.

