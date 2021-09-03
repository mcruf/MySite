---
title: (Talk) Pooling fishery-dependent and -independent data to model species spatio-temporal dynamics - a framework for data boosting and multiple bias correction


#event: Wowchemy Conference
#event_url: https://example.org

location: Salzburg Congress Centre
address:
#  street: 450 Serra Mall
  city: Salzburg
#  region: CA
#  postcode: '94305'
  country: Austria


summary: Talk given to the International Society for Ecological Modelling Global Conference (ISEM-2019).


# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2019-10-03T14:00:00Z"
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
url_pdf: "uploads/talk_ISEM.pdf"
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

The monitoring and assessment of fishery resources rely on two main datasets, namely: commercial fisheries (fishery-dependent) and scientific survey (fishery-independent) data. The monitoring includes mapping the fishery-resources to assess their spatio-temporal dynamics, procedure often conducted through statistical models that usually focus on one data type at a time. Due to their different aims, the sampling design of these data provides distinct levels of bias and consequently hampers their coupling in a joint-likelihood modelling approach. However, if these biases are properly accounted, it is hypothesized that a complete picture and more robust abundance estimates could be achieved by such a model. The main objective hereby was to develop a flexible statistical framework that can compare and integrate these datasets while accounting for their relative bias contributions. As such, a Negative Binomial Cox Process model (NBCP) was designed in Template Model Builder (TMB), where several abundance-related response-variables can be specified and differences in fishing catchability and effort, trawled distance and spatio-temporal correlations can be accounted. Special attention was given to correct the preferential-sampling nature of the fishery-dependent data. To demonstrate its broad applicability, the model was applied on data-rich and -poor stocks from the Kattegat-Western Baltic Sea. For each case study, the NBCP model was tested on (i) commercial, (ii) survey, and (iii) coupled data to assess their differences and evaluate the improvements in abundance estimates. The results revealed that each data source supplied different, yet complementary, information on the species dynamics. Moreover, they confirmed that more precise abundance estimates were obtained by the integrated set-up, especially for the data-poor stocks and where the preferential-sampling bias was considered. Although the fishermen's prevailed sampling behaviour can still be improved, the proposed NBCP model will likely support future stock management and is particularly a benchmark for data-poor stocks due to the boosting of information.




<!--
!{{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

<!--Slides can be added in a few ways:

- **Create** slides using Wowchemy's [*Slides*](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).


Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page.-->
