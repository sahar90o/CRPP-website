---
title: "Saliency-Enhanced Content-Based Image Retrieval for Diagnosis Support in Dermatology Consultation: Reader Study"
authors:
- Javier Barranco Garcia
- Stephanie Tanadini-Lang
- Nicolaus Andratschke
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2023-08-01T00:00:00Z"
doi: "10.2196/42129"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*JMIR Dermatol, 1*(1)"
publication_short: ""

abstract: Previous research studies have demonstrated that medical content image retrieval can play an important role by assisting dermatologists in skin lesion diagnosis. However, current state-of-the-art approaches have not been adopted in routine consultation, partly due to the lack of interpretability limiting trust by clinical users.This study developed a new image retrieval architecture for polarized or dermoscopic imaging guided by interpretable saliency maps. This approach provides better feature extraction, leading to better quantitative retrieval performance as well as providing interpretability for an eventual real-world implementation.
Content-based image retrieval (CBIR) algorithms rely on the comparison of image features embedded by convolutional
neural network (CNN) against a labeled data set. Saliency maps are computer vision–interpretable methods that highlight the
most relevant regions for the prediction made by a neural network. By introducing a fine-tuning stage that includes saliency maps to guide feature extraction, the accuracy of image retrieval is optimized. We refer to this approach as saliency-enhanced CBIR(SE-CBIR). A reader study was designed at the University Hospital Zurich Dermatology Clinic to evaluate SE-CBIR’s retrieval accuracy as well as the impact of the participant’s confidence on the diagnosis.

# Summary. An optional shortened abstract.
summary: In this article we proposed a content base image retrieval algorithm guided by saliency maps (SE-CBIR) which boots the retrieval accuracy by 7% compared to traditional approaches. In addition, a reader study shows that the use of such support tools help participants to improve their diagnosis accuracy while reducing melanoma overdiagnosis

tags:
- Source Themes
featured: True

# links:
# - name: ""
#   url: ""
url_pdf: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10485719/pdf/derma_v6i1e42129.pdf
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

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
