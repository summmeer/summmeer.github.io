---
title: 'Positive, Negative and Neutral: Modeling Implicit Feedback in Session-based News Recommendation'
summary: Detail description about the paper of news recommendation
tags:
  - Deep Learning
  - Recommendation System
date: '2022-03-30T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: 'https://github.com/summmeer/session-based-news-recommendation'

image:
  caption: Demonstration about session-based news reading
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

In this paper, we are interested in exploiting user actions outside the clicks themselves. We call them "implicit feedback". Typical implicit feedback can be extracted from browsing the main page, reading an article, closing an article, backtracking, etc. We believe that modeling such implicit feedback "explicitly" in the session-based recommendation system can help the recommender understand user intention better. In this work, we focus on answering these questions:

- If a user clicked an article, did she really like it?

- If a user did not click an article, did she dislike it?

- How do we model the temporal characteristics of the user and the articles in the system?

First, in traditional recommendation systems, “clicks” usually indicate a “like” or a vote from the user, but things are a bit different for news reading. Users may be “tricked” into clicking an article and once they realize that, they will quickly back out and switch to other articles. Thus the time a user spends on reading an article article, than just the click alone, which is only binary. We model this as the implicit positive feedback in this paper.

Second, just because the user did not click on an article does not necessarily mean the user does not like it; maybe she was never exposed to this article!We can infer what articles might have an impression on the user during a session by by assuming that articles are presented to the user roughly in the order of their publication time. Only those articles within her list of impressions but not clicked are considered "not interesting" to her. This is called implicit negative feedback.

Finally, while the positive and negative feedback helps us estimate the connection between the user and articles, some critical temporal information is useful to model the user and the articles individually. The session start time of a user may suggest the daily routine of that user. We can expect users who read on the same day of a week or same time of a day to have to share the same reading behavior or even background. On the other hand, the publishing time of each article can also be formed into a sequence in a session, which reflects the user’s sensitivity of the timeliness of the stories. We thus carefully design the representation of session start time and article publishing time as implicit neutral feedback.
