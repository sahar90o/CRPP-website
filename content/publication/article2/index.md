---
title: "Generalizable attention U-Net
for segmentation of fibroglandular tissue
and background parenchymal enhancement
in breast DCE-MRI"
authors:
- Sylwia Nowakowska
author_notes:
- "Equal contribution"
date: "2023-06-01T00:00:00Z"
doi: "https://doi.org/10.1186/s13244-023-01531-5"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-06-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Insights into Imaging, 1*(1)"
publication_short: ""

abstract: 
Objectives:Development of automated segmentation models enabling standardized volumetric quantification of fibroglandular tissue (FGT) from native volumes and background parenchymal enhancement (BPE) from subtraction volumes of dynamic contrast-enhanced breast MRI. Subsequent assessment of the developed models in the context of FGT and BPE Breast Imaging Reporting and Data System (BI-RADS)-compliant classification.
Methods:For the training and validation of attention U-Net models, data coming from a single 3.0-T scanner was used. For testing, additional data from 1.5-T scanner and data acquired in a different institution with a 3.0-T scanner was utilized. The developed models were used to quantify the amount of FGT and BPE in 80 DCE-MRI examinations, and a correlation between these volumetric measures and the classes assigned by radiologists was performed.
Results:To assess the model performance using application-relevant metrics, the correlation between the volumes of breast, FGT, and BPE calculated from ground truth masks and predicted masks was checked. Pearson correlation coefficients ranging from 0.963 ± 0.004 to 0.999 ± 0.001 were achieved. The Spearman correlation coefficient for the quantitative and qualitative assessment, i.e., classification by radiologist, of FGT amounted to 0.70 (p < 0.0001), whereas BPE amounted to 0.37 (p = 0.0006).

# Summary. An optional shortened abstract.
summary: In our work, a generalizable attention U-Net model is developed, which can reliably segment breast tissue and contrast uptake of the healthy parenchyma in breast DCE-MRI. Our results suggest that when assessing breast tissue density, it is sufficient to use volumetric measures alone. However, for the evaluation of contrast uptake, additional models considering voxels’ intensity distribution and morphology are required.

tags:
- Source Themes
featured: True

# links:
# - name: ""
#   url: ""
url_pdf: https://insightsimaging.springeropen.com/counter/pdf/10.1186/s13244-023-01531-5.pdf
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
