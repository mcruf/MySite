---
title: (Course) Fisheries data integration - a spatio-temporal SDM framework with the LGNB model


#event: Wowchemy Conference
#event_url: https://example.org

location: Online
#address:
#  street: 450 Serra Mall
#  city: Stanford
#  region: CA
#  postcode: '94305'
#  country: United States


summary: Workshop held for the Statistical Modeling Ecology research Group (SMEG; http://smeg-bayes.org) in April 2021. 


# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2021-04-19T11:00:00Z"
#date_end: "2030-06-01T15:00:00Z"
#all_day: false

# Schedule page publish date (NOT talk date).
#publishDate: "2017-01-01T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#  focal_point: Right

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
#url_code: ""
url_pdf: "uploads/course_LGNB.pdf"
#url_slides: ""
#url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects:
#- internal-project
---


The [**LGNB model**](https://github.com/mcruf/LGNB) is essentially a state-space species distribution model (hence LGNB-SDM) that can integrate two major data sources used within fisheries science, namely fishery-dependent (opportunistic) and fishery-independent (survey) data. Each data source relies on different sampling designs, hampering therefore their integration in a unifying framework. Despite their multiple pitfalls, the two data source provide complementary information which could greatly improve our understading of a species' spatio-temporal dynamics, and ultimately guide better fisheries management practices. The LGNB-SDM was thus developed with the main goal to bridge the gap between the two data sources. Within the LGNB-SDM framework,the relative bias contribution of a species' abundance estimator is filtered out with respect to each data source, providing as such improved abundance estimates and knowledge on it's spatial distribution.




<!--
!{{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

<!--Slides can be added in a few ways:

- **Create** slides using Wowchemy's [*Slides*](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).


Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page.-->
