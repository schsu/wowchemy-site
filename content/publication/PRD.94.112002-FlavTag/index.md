---
title: Jet Flavor Classification in High-Energy Physics with Deep Neural Networks
authors:
- admin
#author_notes:
#- "Event Selection optimization"
date: "2016-12-02T00:00:00Z"
doi: "10.1103/PhysRevD.94.112002"

# Schedule page publish date (NOT publication's date).
publishDate: "2016-12-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Physical Review D"
publication_short: "PRD"

abstract: Classification of jets as originating from light-flavor or heavy-flavor quarks is an important task for inferring the nature of particles produced in high-energy collisions. The large and variable dimensionality of the data provided by the tracking detectors makes this task difficult. The current state-of-the-art tools require expert data reduction to convert the data into a fixed low-dimensional form that can be effectively managed by shallow classifiers. We study the application of deep networks to this task, attempting classification at several levels of data, starting from a raw list of tracks. We find that the highest-level lowest-dimensionality expert information sacrifices information needed for classification, that the performance of current state-of-the-art taggers can be matched or slightly exceeded by deep-network-based taggers using only track and vertex information, that classification using only lowest-level highest-dimensionality tracking information remains a difficult task for deep networks, and that adding lower-level track and vertex information to the classifiers provides a significant boost in performance compared to the state of the art.


# Summary. An optional shortened abstract.
summary: We studied the application of deep networks to heavy-flavor jets classification byadding lower-level track and vertex information to the high-level features and showed a significant boost in performance compared to the state of the art.


tags:
- Deep Learning
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/abs/1607.08633 
#url_code: ''
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
#url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Signal efficiency versus background rejection (inverse of efficiency) for deep networks trained on track-level, vertex-level or expert-level features.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [Deep Learning]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
