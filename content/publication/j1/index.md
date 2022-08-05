---
title: "Robust Dynamic CPU Resource Provisioning in Virtualized Servers"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Kyriakos M Deliparaschos
- Evangelia Kalyvianaki
- Argyrios Zolotas
- Themistoklis Charalambous

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2020-01-15T00:00:00Z"
doi: "10.1109/TSC.2020.2966972"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Services Computing (TSC)*
#publication_short: In *ETFA*

abstract: We present robust dynamic resource allocation mechanisms to allocate application resources meeting Service Level Objectives (SLOs) agreed between cloud providers and customers. In fact, two filter-based robust controllers, i.e. H∞ filter and Maximum Correntropy Criterion Kalman filter (MCC-KF), are proposed. The controllers are self-adaptive, with process noise variances and covariances calculated using previous measurements within a time window. In the allocation process, a bounded client mean response time (mRT) is maintained. Both controllers are deployed and evaluated on an experimental testbed hosting the RUBiS (Rice University Bidding System) auction benchmark web site. The proposed controllers offer improved performance under abrupt workload changes, shown via rigorous comparison with current state-of-the-art. On our experimental setup, the Single-Input-Single-Output (SISO) controllers can operate on the same server where the resource allocation is performed; while Multi-Input-Multi-Output (MIMO) controllers are on a separate server where all the data are collected for decision making. SISO controllers take decisions not dependent to other system states (servers), albeit MIMO controllers are characterized by increased communication overhead and potential delays. While SISO controllers offer improved performance over MIMO ones, the latter enable a more informed decision making framework for resource allocation problem of multi-tier applications.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Resource provisioning,virtualized servers,CPU allocation,CPU usage,RUBiS,Robust prediction,H1 filter,MCC-KF,Kalman filter]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/8960454'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

# {{% callout note %}}
# Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /callout %}}

# {{% callout note %}}
# Create your slides in Markdown - click the *Slides* button to check out the example.
# {{% /callout %}}

# Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
