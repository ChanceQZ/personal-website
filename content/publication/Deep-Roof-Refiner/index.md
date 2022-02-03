---
title: "Deep Roof Refiner: A detail-oriented deep learning network for refined delineation of roof structure lines using satellite imagery"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Min Chen
- Teng Zhong
- Fan Zhang
- Rui Zhu
- Zhixin Zhang
- Kai Zhang
- Zhuo Sun
- Guonian Lü

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2022-03-01T00:00:00Z"
doi: "https://doi.org/10.1016/j.jag.2022.102680"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-02-03T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *International Journal of Applied Earth Observation and Geoinformation*
publication_short: In *JAG*

abstract: Urban research is progressively moving towards fine-grained simulation and requires more granular and accurate geospatial data. In comparison to building footprints, roof structure lines (RSLs) are finer-grained elements of building roofs that provide a more sophisticated data reference. However, generating high-quality and up-to-date RSLs is arduous owing to the high expense of data sources (e.g., digital surface models and light detection and ranging data) and the low robustness of conventional image processing approaches. While the current combination of high-resolution satellite imagery and deep learning methods enables the automatic generation of RSLs, it also introduces two distinct challenges. First, the high diversity of roof sizes, forms, and spatial distribution complicates the extraction of essential RSL features from satellite imagery using general deep learning methods. Second, the significant class imbalance issue between foreground objects (i.e., RSLs) and background context in satellite imagery makes it difficult for deep learning methods to concentrate on RSL locations. To overcome these challenges and effectively delineate RSLs from satellite imagery, this study designs Deep Roof Refiner—an end-to-end and detail-oriented deep learning network and proposes a synthetic strategy to enhance the network’s performance. The effectiveness of the proposed network is verified by quantitative and qualitative experiments, with the optimal dataset scale F1-score and optimal image scale F1-score of 60.89% and 63.48%, respectively. The proposed network significantly outperforms state-of-the-art deep learning methods and associated conventional research. The results indicate that the delineated RSLs can serve as a reliable data source for some urban building-based studies.

# Summary. An optional shortened abstract.
summary: To overcome these two challenges of delineating roof structure lines from satellite imagery, the Deep Roof Refiner—a detail-oriented deep learning network and a synthetic strategy were proposed.

tags: ["Deep learning", "Roof Structure Lines", "Satellite Imagery", "Fine-grained Geospatial Data"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.sciencedirect.com/science/article/pii/S030324342200006X/pdfft?md5=8adafade495811d6b0a8882947383864&pid=1-s2.0-S030324342200006X-main.pdf'
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
  caption: 'Image credit: [**Workflow**](https://ars.els-cdn.com/content/image/1-s2.0-S030324342200006X-gr5_lrg.jpg)'
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

