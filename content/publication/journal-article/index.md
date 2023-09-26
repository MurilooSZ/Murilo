---
title: "Development of a device to determine the body score of cattle"
authors:
- admin
- Jofran Luiz de Oliveira
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2021-12-23T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-12-23T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Annals of the UFR Teaching, Research, Extension and Innovation Congress (CONNECT UFR), 1*(1)"
publication_short: ""

  abstract: 'Precision livestock farming is a concept defined by the automation of practices that
consider, when possible, the variability of individualized responses from
animals. In current livestock farming, its use is essential for the producer to achieve better
results, maximizing economic gains and minimizing damage to animals and
to the environment. The body condition score (BCS) is associated with the condition
nutrition of animals. Furthermore, research highlights the benefits of measuring
of the ECC in numerous characteristics, such as health, production, ability
maternal, food consumption, reproduction and carcass gain of ruminants. A
The practice of evaluating the BCS of cattle is generally done visually or tactilely,
obtaining values on a scale from 1 (very thin) to 5 (very fat). However the
What we are looking for is moderate body condition score values, as these
reflect the metabolic balance of the bovine, providing better performance
reproductive system, greater milk production, offspring with good development and better
carcass quality. Considering that the ECC assessment is quite subjective,
Depending on the experience and judgment of the evaluator, it is necessary to study
means for automating the bovine ECC identification process using
computer vision techniques. The general objective of this work is to carry out the study
in-depth understanding of computer vision techniques for developing and evaluating
software and device prototype that can determine the score
body of the bovine individually and in real time. Search for how to get
reliable ECC answers based on the evaluation of an image bank of
cattle taking into account nutritional variability with pre-defined BCS. To the
To carry out this work, a notebook and computer programs were used.
open source like Python available on Google Colab, the vision library
computational OpenCV version 4.5.3, the Numpy library version 1.21 and the database
images of cattle with pre-defined BCS. Firstly, the selection was carried out
of the 207 images contained in the database with variation in ECC score.
We sought to select images with better sharpness, luminosity, lower degree of
blur and greater capture stability, resulting in 23 images. The algorithm
developed was able to remove the background of images with the aim of
obtain only the figure of the animal present in the photo. Then, the
thresholding or binarization techniques, a function was later coded
to detect the image contour area, eliminating the noise area and the
calculated was used as the response variable. The obtained results
demonstrated a good direct linear correlation between the detected area and the pre-defined ECC, confirming the viability of the algorithm. Due to the COVID-19 epidemic,
It was not possible to carry out the field test, however the laboratory test with the
images obtained from the database demonstrated that the developed prototype has
potential for automating the ECC assessment process, which will enable the
producer an aid in decision-making regarding the management of his herd and
consequently increased productivity and profitability.'


# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
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
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
