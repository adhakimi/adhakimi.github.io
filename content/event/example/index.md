---
title: TimeCourse MechInterp

event: IT University of Copenhagen - NLP Talks
#event_url: https://example.org

location: Copenhagen
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

abstract: 'Understanding how large language models (LLMs) acquire and store factual knowledge is crucial for enhancing their interpretability and reliability. In this work, we analyze the evolution of factual knowledge representation in the OLMo-7B model by tracking the roles of its attention heads and feed forward networks (FFNs) over the course of pre-training. We classify these components into four roles: general, entity, relation-answer, and fact-answer specific and examine their stability and transitions. Our results show that LLMs initially depend on broad, general-purpose components, which later specialize as training progresses. Once the model reliably predicts answers, some components are repurposed, suggesting an adaptive learning process. Notably, attention heads display the highest turnover. We also present evidence that FFNs remain more stable throughout training. Furthermore, our probing experiments reveal that location-based relations converge to high accuracy earlier in training than namebased relations, highlighting how task complexity shapes acquisition dynamics. These insights offer a mechanistic view of knowledge formation in LLMs.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2030-06-01T13:00:00Z'
#date_end: '2030-06-01T15:00:00Z'
#all_day: false

# Schedule page publish date (NOT talk date).
#publishDate: '2017-01-01T00:00:00Z'

#

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - example
---

{{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page.
