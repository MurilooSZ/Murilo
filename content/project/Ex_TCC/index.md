---
title: Computer Vision
summary: An example of using the in-built project page.
tags:
  - Deep Learning
  - OpenCV
  - “You Only Look Once” – YOLO
date: '2022-11-18T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
  - icon: library
    icon_pack: fab
    name:  Pergamum
    url: https://biblioteca.ufr.edu.br/acervo/323881
url_code: ''
url_pdf: 'https://biblioteca.ufr.edu.br/pergamumweb/vinculos/00003b/00003bf4.pdf'
url_slides: 'https://drive.google.com/file/d/1-rvIhY8wCxSKmzNJuYv7eBXu8F4z1-3K/view?usp=sharing'
url_video: 'https://drive.google.com/file/d/19ezy9FiWmQX1CM1T056eM7hasfjQM3ii/view?usp=sharing'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

Soy is an important source of protein used in animal and human nutrition, in addition to being used in the production of cooking oil and biofuels. Weeds are any non-cultivated plants that grow in crops, and it is essential to identify them to determine the best management, aiming to reduce losses and improve economic viability.

Recently, there have been advances in the use of computer vision in agribusiness, such as the retrieval of three-dimensional information and recognition of elements in images. Artificial Neural Networks (ANNs) are mathematical models inspired by biological neurons, capable of identifying patterns in unknown data, making predictions and processing information.

An image bank of weed species was built, with images annotated using the CVAT tool. The images were categorized into broad- and narrow-leaf weeds. The YoloV4 model was configured and trained with these images, performing 12,000 iterations for each class.

The results showed good performance in the "current average loss" (0.819) and Intersection Over Union (IoU) (67.54%) evaluation metrics. However, the mAP metric (42.52%) was lower than expected, indicating that the model's accuracy was low, especially for the prediction of narrow-leaved weeds. Despite this, the model demonstrated good performance in the challenge of detecting broad- and narrow-leaved weeds using deep learning.
