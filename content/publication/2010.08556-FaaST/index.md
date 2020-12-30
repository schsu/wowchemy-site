---
title: "FPGAs-as-a-Service Toolkit (FaaST)" 
authors:
- admin
- ScottHauck
- MatthewTrahms
- KelvinLin
- YuLou
- TaWeiHo

date: "2020-10-06T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-10-06T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Computing needs for high energy physics are already intensive and are expected to increase drastically in the coming years. In this context, heterogeneous computing, specifically as-a-service computing, has the potential for significant gains over traditional computing models. Although previous studies and packages in the field of heterogeneous computing have focused on GPUs as accelerators, FPGAs are an extremely promising option as well. A series of workflows are developed to establish the performance capabilities of FPGAs as a service. Multiple different devices and a range of algorithms for use in high energy physics are studied. For a small, dense network, the throughput can be improved by an order of magnitude with respect to GPUs as a service. For large convolutional networks, the throughput is found to be comparable to GPUs as a service. This work represents the first open-source FPGAs-as-a-service toolkit.

# Summary. An optional shortened abstract.
summary: Heterogeneous computing has the potential for significant gains over traditional computing models. This work represents the first open-source FPGAs-as-a-service toolkit.

tags:
- Source Themes
featured: true

links:
- name: Custom Link
  url: https://arxiv.org/abs/2010.08556
url_pdf: https://arxiv.org/abs/2010.08556 
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Total processing time required with AWS f1 (left) and throughput achieved with a Alveo U250 (right) for running a realistic HLT workflow using the FACILE FaaST server as a function of the number of simultaneous clients.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- FastML
- ASAML

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
