---
title: "Identification of urban functional areas by coupling satellite images and taxi GPS trajectories"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Xintao Liu
- Fei Tao
- Tong Zhou

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2020-07-30T00:00:00Z"
doi: "https://doi.org/10.3390/rs12152449"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-02-03T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Remote Sensing*
publication_short: In *RS*

abstract: Urban functional area (UFA) recognition is one of the most important strategies for achieving sustainable city development. As remote-sensing and social-sensing data sources have increasingly become available, UFA recognition has received a significant amount of attention. Research on UFA recognition that uses a single dataset suffers from a low update frequency or low spatial resolution, while data fusion-based methods are limited in efficiency and accuracy. This paper proposes an integrated model to identify UFA using satellite images and taxi global positioning system (GPS) trajectories in four steps. First, blocks were generated as spatial units in the study area, and the spatiotemporal information entropy of the taxi GPS trajectory (STET) for each block was calculated. Second, a 24-hour time-frequency series was formed based on the pick-up and drop-off points extracted from taxi trajectories and used as the interpretation indicator of the blocks. The K-Means++ and k-Nearest Neighbor (kNN) algorithm were used to identify their social functions. Third, a multilabel classification method based on the residual neural network (MLC-ResNets) and “You Only Look Once” (YOLO) target detection algorithms were used to identify the features of the typical and atypical spatial textures, respectively, of the satellite images in the blocks. The confidence scores of the features of the blocks were categorized by the decision tree algorithm. Fourth, to find the best way to integrate the two sub-models for UFA identification, the 10-fold cross-validation method based on stratified random sampling was applied to determine the most optimal STET thresholds. The results showed that the average accuracy reached 82.0%, with an average kappa of 73.5%—significant improvements over most existing studies. This paper provides new insights into how the advantages of satellite images and taxi trajectories in UFA identification can be fully exploited to support sustainable city management.

# Summary. An optional shortened abstract.
summary: This paper provides new insights into how the advantages of satellite images and taxi trajectories in UFA identification can be fully exploited to support sustainable city management.

tags: ["Urban Function Areas", "Remote Sensing", "Taxi Trajectory", "Machine Learning"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Workflow**](https://www.mdpi.com/remotesensing/remotesensing-12-02449/article_deploy/html/images/remotesensing-12-02449-ag.png)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

