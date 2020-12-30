---
title: FPGA-Accelerated Machine Learning Inference as a Service for Particle Physics Computing
authors:
- admin
- ScottHauck
- DustinWerran
- Matthew Trahms

author_notes:
- "Superviser"
- "Collaborator"
- "ResNet-50 quantization"
- "Resnet-50 optimization"
date: "2019-10-14T00:00:00Z"
doi: "10.1007/s41781-019-0027-2"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-10-14T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Physical Review Letters"
publication_short: "CSBS"

abstract: Large-scale particle physics experiments face challenging demands for high-throughput computing resources both now and in the future. New heterogeneous computing paradigms on dedicated hardware with increased parallelization, such as Field Programmable Gate Arrays (FPGAs), offer exciting solutions with large potential gains. The growing applications of machine learning algorithms in particle physics for simulation, reconstruction, and analysis are naturally deployed on such platforms. We demonstrate that the acceleration of machine learning inference as a web service represents a heterogeneous computing solution for particle physics experiments that potentially requires minimal modification to the current computing model. As examples, we retrain the ResNet-50 convolutional neural network to demonstrate state-of-the-art performance for top quark jet tagging at the LHC and apply a ResNet-50 model with transfer learning for neutrino event classification. Using Project Brainwave by Microsoft to accelerate the ResNet-50 image classification model, we achieve average inference times of 60 (10) ms with our experimental physics software framework using Brainwave as a cloud (edge or on-premises) service, representing an improvement by a factor of approximately 30 (175) in model inference latency over traditional CPU inference in current experimental hardware. A single FPGA service accessed by many CPUs achieves a throughput of 600–700 inferences per second using an image batch of one, comparable to large batch-size GPU throughput and significantly better than small batch-size GPU throughput. Deployed as an edge or cloud service for the particle physics computing model, coprocessor accelerators can have a higher duty cycle and are potentially much more cost-effective.

# Summary. An optional shortened abstract.
summary: Large-scale particle physics experiments face challenging demands for high-throughput computing resources both now and in the future. New heterogeneous computing paradigms on dedicated hardware with increased parallelization, such as Field Programmable Gate Arrays (FPGAs), offer exciting solutions with large potential gains. Using Project Brainwave by Microsoft to accelerate the ResNet-50 image classification model. 


tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/abs/1904.08986 
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
  caption: 'An illustration of FPGA-accelerated ML cloud resources as a service (left). Throughput of the FPGA service as the number of ResNet-50 inferences per second for different numbers of simultaneous processes on the Brainwave system (right).'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [FastML]

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
