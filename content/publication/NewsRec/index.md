---
title: 'Positive, Negative and Neutral: Modeling Implicit Feedback in Session-based News Recommendation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Shansan Gong
  - Kenny Q. Zhu

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-07-01T00:00:00Z'
doi: '10.1145/3477495.3532040'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 45th International ACM SIGIR Conference on Research and Development in Information Retrieval*
publication_short: In *SIGIR*

abstract: News recommendation for anonymous readers is a useful but challenging task for many news portals, where interactions between readers and articles are limited within a temporary login session. Previous works tend to formulate session-based recommendation as a next item prediction task, while they neglect the implicit feedback from user behaviors, which indicates what users really like or dislike. Hence, we propose a comprehensive framework to model user behaviors through positive feedback (i.e., the articles they spend more time on) and negative feedback (i.e., the articles they choose to skip without clicking in). Moreover, the framework implicitly models the user using their session start time, and the article using its initial publishing time, in what we call neutral feedback. Empirical evaluation on three real-world news datasets shows the framework's promising performance of more accurate, diverse and even unexpectedness recommendations than other state-of-the-art session-based recommendation approaches.

# Summary. An optional shortened abstract.
summary: We propose a comprehensive framework to model user behaviors through implicit feedback. Empirical evaluation on three real-world news datasets shows the framework's promising performance of more accurate, diverse and even unexpectedness recommendations than other state-of-the-art session-based recommendation approaches.

tags: ['Recommendation System']

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://summmeer.github.io/publication/NewsRec/paper_news_final.pdf'
url_code: 'https://github.com/summmeer/session-based-news-recommendation'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Demonstration of the session-based news reading.'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - NewsRec

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
