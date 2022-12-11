---
title: "Onboard Real-Time Multi-Sensor Pose Estimation for Indoor Quadrotor Navigation with Intermittent Communication"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Loizos Hadjiloizou
- Kyriakos Deliparaschos
- admin
- Themistoklis Charalambous

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2022-12-03T00:00:00Z"
doi: "https://arxiv.org/abs/2212.01599"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Global Communications Conference (GLOBECOM)*

abstract: We propose a multisensor fusion framework for onboard real-time navigation of a quadrotor in an indoor environment, by integrating sensor readings from an Inertial Measurement Unit (IMU), a camera-based object detection algorithm, and an Ultra-WideBand (UWB) localization system. The sensor readings from the camera-based object detection algorithm and the UWB localization system arrive intermittently, since the measurements are not readily available. We design a Kalman filter that manages intermittent observations in order to handle and fuse the readings and estimate the pose of the quadrotor for tracking a predefined trajectory. The system is implemented via a Hardware-in-the-loop (HIL) simulation technique, in which the dynamic model of the quadrotor is simulated in an open-source 3D robotics simulator tool, and the whole navigation system is implemented on Artificial Intelligence (AI) enabled edge GPU. The simulation results show that our proposed framework offers low positioning and trajectory errors, while handling intermittent sensor measurements.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [quadrotor navigation, indoor localization, sensor fusion, pose estimation.]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
#- name: Demo Video
#  url: https://www.youtube.com/watch?v=pEBHR3MTPuA

url_pdf: 'https://arxiv.org/pdf/2212.01599.pdf'
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
