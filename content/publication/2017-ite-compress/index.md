---
title: "Traffic flow data compression considering burst components"
authors:
- Shuo Feng
- Ruimin Ke
- admin
- Yi Zhang
- Li Li

date: "2017-11-01T00:00:00Z"
doi: "https://doi.org/10.1049/iet-its.2016.0328"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IET Intelligent Transport Systems* **11**(9)"
publication_short: ""

abstract: Many recent applications of intelligent transportation systems require both real-time and network-wide traffic flow data as input. However, as the detection time and network size increase, the data volume may become very large in terms of both dimension and scale. To address this concern, various traffic flow data compression methods have been proposed, which archive the low-dimensional subspace rather than the original data. Many studies have shown the traffic flow data consist of different components, i.e. low-dimensional intra-day trend, Gaussian type fluctuation and burst components. Existing compression methods cannot compress the burst components well and provide very limited choices of compression ratio (CR). A better compression method should have the ability to archive all the dominant information in different components of traffic flow data. In this study, the authors compare the influence of different data reformatting, archive the bursts defined before in descending order with respect to the absolute value of the burst points and propose a flexible compression framework to balance between burst components and low-dimensional intra-day trend. Experimental results show that the proposed framework promotes the reconstruction accuracy significantly. Moreover, the proposed framework provides more flexible choices with respect to CR, which can benefit a variety of applications.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
# - Trajectory Data
# - Estimation
featured: false

# links:
# - name: ""
#   url: ""
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
