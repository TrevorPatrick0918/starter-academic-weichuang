---
abstract: >-
  Recently, researchers have been dedicated to discovering Generative
  Adversarial Network (GAN) artifacts and using them to identify generated
  images, which aims to avoid the potential abuse of GAN-generated images.
  However, current approaches exhibit restricted performance when testing
  against unforeseen GAN models, which is also known as the cross-domain
  scenario. To overcome this limitation, we proposed a novel

  detection framework of GAN-generated images by estimating artifact similarity, which is inspired by relation network. The proposed method consists of two stages, including representation learning and representation comparison. The first stage embeds the input images into representations through residual network cooperated with Instance Normalization (IN) layer and calculates prototypes of different domains separately, where the prototype serves as a reference representation of one domain. Then, in the second stage, the representation of the consult image is concatenated with prototypes of different domains and then fed

  into the scorer network individually to calculate the similarity scores. The average score over different domains is used to obtain the final detection result. Extensive experiments are conducted which consider various cross-domain scenarios to verify the better generalization capability of the proposed method to unseen GAN models. Besides, our method can also achieve a distinct performance gain with common post-processing operations.
slides: example
url_pdf: ""
publication_types:
  - "3"
authors:
  - Weichuang Li
  - Peisong He
  - Haoliang Li
  - Hongxia Wang
  - and Ruimei Zhang
author_notes:
  - Equal contribution
  - Equal contribution
publication: In **
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere
  tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin
  condimentum.
url_dataset: ""
url_project: ""
publication_short: In **
url_source: ""
url_video: ""
title: Detection of GAN-generated Images by Estimating Artifact Similarity
doi: ""
featured: true
tags: []
projects:
  - example
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
  focal_point: ""
  preview_only: false
date: 2013-07-01T00:00:00Z
url_slides: ""
publishDate: 2017-01-01T00:00:00Z
url_poster: ""
url_code: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
