---
title: "Learning the max pressure control for urban traffic networks considering the phase switching loss"
authors:
- admin
- Yafeng Yin
- Yiheng Feng
- Henry X Liu
date: "2022-07-01T00:00:00Z"
doi: "https://doi.org/10.1016/j.trc.2022.103670"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Transportation Research Part C: Emerging Technologies* **140**"
publication_short: ""

abstract: Previous studies have shown that the max pressure control is a throughput-optimal policy that can stabilize the store-and-forward traffic network when the demand is within the network capacity. Most of the existing studies on the max pressure control do not consider the loss of capacity associated with phase switching, which will undermine the stability of the network. This work proposes a novel framework that utilizes reinforcement learning algorithms to optimize a max pressure controller considering the phase switching loss. We extend the max pressure control by introducing a switching curve and prove that the proposed control method is throughput-optimal in a store-and-forward network. Then the theoretical control policy is extended by using a distributed approximation and position-weighted pressure so that the policy-gradient reinforcement learning algorithms can be utilized to optimize the parameters in the policy network including the switching curve and the weight curve. Simulation results show that the proposed control method greatly outperforms the conventional max pressure control. The proposed framework combines the strengths of the data-driven method and the theoretical control model by utilizing reinforcement learning algorithm to optimize the max pressure controller, which is also of great significance for real-world implementations because the proposed control policy can be generated in a distributed fashion based on local observations.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Traffic Signal
- Max Pressure Control
- Reinforcement Learning
featured: true

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
