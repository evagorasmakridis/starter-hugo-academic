---
title: "Maximum Correntropy Criterion Kalman Filter For Indoor Quadrotor Navigation Under Intermittent Measurements"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Loizos Hadjiloizou
- admin
- Themistoklis Charalambous
- Kyriakos Deliparaschos

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2023-03-03T00:00:00Z"
doi: "https://arxiv.org/abs/2303.09561"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *arXiv Preprint*

abstract: We present a multisensor fusion framework for the onboard real-time navigation of a quadrotor in an indoor environment. The framework integrates sensor readings from an Inertial Measurement Unit (IMU), a camera-based object detection algorithm, and an Ultra-WideBand (UWB) localisation system. Often the sensor readings are not always readily available, leading to inaccurate pose estimation and hence poor navigation performance. To effectively handle and fuse sensor readings, and accurately estimate the pose of the quadrotor for tracking a predefined trajectory, we design a Maximum Correntropy Criterion Kalman Filter (MCC-KF) that can manage intermittent observations. The MCC-KF is designed to improve the performance of the estimation process when is done with a Kalman Filter (KF), since KFs are likely to degrade dramatically in practical scenarios in which noise is non-Gaussian (especially when the noise is heavy-tailed). To evaluate the performance of the MCC-KF, we compare it with a previously designed Kalman filter by the authors. Through this comparison, we aim to demonstrate the effectiveness of the MCC-KF in handling indoor navigation missions. The simulation results show that our presented framework offers low positioning errors, while effectively handling intermittent sensor measurements.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [quadrotor navigation, indoor localization, sensor fusion, pose estimation, maximum correntropy criterion kalman filter.]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
#- name: Demo Video
#  url: https://www.youtube.com/watch?v=pEBHR3MTPuA

url_pdf: 'https://arxiv.org/pdf/2303.09561.pdf'
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
