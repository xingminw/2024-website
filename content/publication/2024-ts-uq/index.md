---
title: "Traffic State Estimation and Uncertainty Quantification at Signalized Intersections with Low Penetration Rate Vehicle Trajectory Data"
authors:
- admin
- Zihao Wang
- Zachary Jerome
- Henry Liu
date: "2024-04-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-04-02T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "Submitted to Transportation Science"
publication_short: ""

abstract: This paper studies the traffic state estimation problem at signalized intersections with low penetration rate vehicle trajectory data. While many existing studies have proposed different methods to estimate unknown traffic states and parameters (e.g., penetration rate, queue length) with this data, most of them only provide a point estimation without knowing the uncertainty of these estimated values. It is important to quantify the estimation uncertainty caused by limited available data since it can explicitly inform us whether the available data is sufficient to satisfy the desired estimation accuracy. To fill this gap, we formulate the partially observable system as a hidden Markov model (HMM) based on the recently developed probabilistic time-space (PTS) model. The PTS model is a stochastic traffic flow model that is designed for modeling traffic flow dynamics near signalized intersections. Based on the HMM formulation, a single recursive program is developed for the Bayesian estimation of both traffic states and parameters. As a Bayesian approach, the proposed method provides the distributional estimation outcomes and directly quantifies the estimation uncertainty. We validate the proposed method with simulation studies and showcase its applicability to real-world vehicle trajectory data.

# Summary. An optional shortened abstract.
summary: In this paper, we aim to answer one critical question - whether the available low penetration rate vehicle trajectory data is sufficient to estimate those unknown traffic states and parameters near signalized intersections. 

tags:
- Trajectory Data
- Traffic Signal
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/2404.08667
url_pdf: https://arxiv.org/pdf/2404.08667.pdf
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Traffic State Estimation and Uncertainty Quantification'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->