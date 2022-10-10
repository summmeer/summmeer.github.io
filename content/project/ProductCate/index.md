---
title: 'Dynamic Product Categorization for Multiple Domain'
summary: Detail description about the internship in Meituan
tags:
  - Deep Learning
  - Hierarchical Classification
  - E-commerce
date: '2022-05-30T00:00:00Z'

# Optional external URL for project (replaces project detail page).
# external_link: 'https://github.com/summmeer/session-based-news-recommendation'

# image:
#   caption: Demonstration about session-based news reading
#   focal_point: Smart

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

Product categorization is to assign a product with a suitable category, which is usually organized in a predefined taxonomy. As e-commerce platforms develop different business lines, a special but challenging categorization scenario emerges, where there are multiple domain-specific category taxonomies and each of them evolves dynamically over time. 

In order to unify the categorization process and jointly utilize the cross-domain data, we propose a two-stage taxonomy-agnostic framework that relies solely on calculating the semantic relatedness between product titles and category names in the vector space. 

However, pure vector matching may fall for the surface form of text, and we thus further leverage the universal “knowledge” across different business domains to complement textual semantics. We design a heuristic retrieval strategy and pretrain a contrastive ranking model with the help of “concept”, which resembles the shared keyword knowledge cross domains. 

Our comprehensive experiments show that our method outperforms existing sophisticated approaches quantitatively and efficiently on dynamical multi-domain taxonomies.