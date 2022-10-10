---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: NLP Researcher
    company: Shanghai AI Lab
    company_url: ''
    company_logo: ailab
    location: Shanghai
    date_start: '2022-06-01'
    date_end: ''
    description: Mainly interested in diffusion model and controllable text generation. Responsible for sequence-to-sequence text generation tasks based on diffusion models.

  - title: Research Engineer
    company: Meituan
    company_url: ''
    company_logo: meituan
    location: Shanghai
    date_start: '2021-12-06'
    date_end: '2022-03-08'
    description: Responsible for an unified product categorization framework for multiple domains.

  - title: Software Engineer
    company: Microsoft
    company_url: ''
    company_logo: Microsoft
    location: Beijing
    date_start: '2021-06-01'
    date_end: '2021-10-01'
    description: |2-
        Responsible for a user query intention recognition task, in order to optimize the search result.

        * The task is about cross-language query intent recognition, and we introduce **PostWeb** information (ie, text information such as the title, link, and abstract of the query search result) as an additional feature of the query.
        * The classification model increases the AUC by about 1% on the test data set, while achieve around 5% improvement on financial stock test data set.
  
  - title: CTO
    company: Iwenbooks
    company_url: 'http://adapt.seiee.sjtu.edu.cn/iwen/'
    company_logo: iwen
    location: Shanghai
    date_start: '2019-12-01'
    date_end: '2022-03-01'
    description: |2-
        Iwen is a book and news reading APP, which currently provides service for more than 20,000 users. My responsibility includes:

        * Design the database structure based on MongoDB and develop API using Node.js.
        * Implement the vanilla book/news recommendation system, which is based on a hybrid strategy combining collaborative filtering and user portraits.
        * Meeting arrangement and program management.

design:
  columns: '2'
---
