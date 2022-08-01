---
title: "Vectorized dataset of roadside noise barriers in China using street view imagery"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Min Chen
- Yue Yang
- Teng Zhong
- Fan Zhang
- Rui Zhu
- Kai Zhang
- Zhixin Zhang
- Zhuo Sun
- Peilong Ma
- Guonian Lü
- Yu Ye
- Jinyue Yan

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2022-04-11T00:00:00Z"
doi: "https://doi.org/10.5194/essd-2022-19"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-04-11T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *Earth System Science Data*
publication_short: In *ESSD*

abstract: Roadside noise barriers (RNBs) are important urban infrastructures to develop a liveable city. However, the absence of accurate and large-scale geospatial data on RNBs has impeded the increasing progress of rational urban planning, sustainable cities, and healthy environments. To address this problem, this study proposes a geospatial artificial intelligence framework to create a vectorized RNB dataset in China using street view imagery. To begin, intensive sampling is performed on the road network of each city based on OpenStreetMap, which is used as the geo-reference to download 5.6 million Baidu Street View (BSV) images. Furthermore, considering the prior geographic knowledge contained in street view images, convolutional neural networks incorporating image context information (IC-CNNs) based on an ensemble learning strategy are developed to detect RNBs from the BSV images. Subsequently, the RNB dataset presented by polylines is generated based on the identified RNB locations, with a total length of 2,227 km in 215 cities. At last, the quality of the RNB dataset is evaluated from two perspectives, first, the detection accuracy; second, the completeness and positional accuracy. Specifically, based on a set of randomly selected samples containing 10,000 BSV images, four quantitative metrics are calculated, with an overall accuracy of 98.61 %, recall of 87.14 %, precision of 76.44 %, and F1-score of 81.44 %. Moreover, a total length of 254 km of roads in different cities are manually surveyed using BSV images to evaluate the mileage deviation and overlap level between the generated and surveyed RNBs. The root-mean-squared error for mileage deviation is 0.08 km, and the intersection over union for overlay level is 88.08 % ± 2.95 %. The evaluation results suggest that the generated RNB dataset is of high quality and can be applied as an accurate and reliable dataset for a variety of large-scale urban studies. The generated vectorized RNB dataset and the labelled BSV image benchmark dataset are publicly available at https://doi.org/10.11888/Others.tpdc.271914 (Chen, 2021).

# Summary. An optional shortened abstract.
summary: Roadside noise barriers (RNBs) are important urban infrastructures to develop a liveable city. This study provides the first reliable and nationwide vectorized RNB dataset by street view imagery in China. The generated RNB dataset is evaluated in two aspects, i.e., the detection accuracy, as well as the completeness and positional accuracy. The method is based on a developed geospatial artificial intelligence framework.

tags: ["Deep learning", "Roadside Noise Barrier", "Street View Imagery"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://essd.copernicus.org/preprints/essd-2022-19/essd-2022-19.pdf'
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
  caption: 'Image credit: [**Workflow**](featured.jpg)'
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

