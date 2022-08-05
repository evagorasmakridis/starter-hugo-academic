---
title: "Dynamic CPU Resource Provisioning in Virtualized Servers using Maximum Correntropy Criterion Kalman Filters"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Kyriakos M Deliparaschos
- Evangelia Kalyvianaki
- Themistoklis Charalambous

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2017-09-12T00:00:00Z"
doi: "10.1109/ETFA.2017.8247677"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *22nd IEEE International Conference on Emerging Technologies and Factory Automation (ETFA)*
#publication_short: In *ETFA*

abstract: Virtualized servers have been the key for the efficient deployment of cloud applications. As the application demand increases, it is important to dynamically adjust the CPU allocation of each component in order to save resources for other applications and keep performance high, e.g., the client mean response time (mRT) should be kept below a Quality of Service (QoS) target. In this work, a new form of Kalman filter, called the Maximum Correntropy Criterion Kalman Filter (MCC-KF), has been used in order to predict, and hence, adjust the CPU allocations of each component while the RUBiS auction site workload changes randomly as the number of clients varies. MCC-KF has shown high performance when the noise is non-Gaussian, as it is the case in the CPU usage. Numerical evaluations compare our designed framework with other current state-of-the-art using real-data via the RUBiS benchmark website deployed on a prototype Xen-virtualized cluster.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Resource provisioning,virtualized servers,CPU allocation,CPU usage,RUBiS,Kalman filter]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/8247677'
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

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
