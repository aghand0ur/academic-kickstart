---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Building Footprints"
summary: ""
authors: []
tags: []
categories: []
date: 2020-10-27T10:59:15+01:00

# Optional external URL for project (replaces project detail page).
#external_link: "https://pribot.org/polisis"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
The first comprehensive Lebanese Building Footprints map was autonomously generated using Deep Learning Models that were developed and tested at the Lebanese National Remote Sensing Center - CNRS.
We trained fully convolutional 'Encoder-Decoder' like Neural Networks on GEOEYE-1 high resolution satellite images (50 cm/pixel) from the Year 2013 for semantic segmentation of urban areas.

When you ZOOM IN, the dots on the map refer to the centroids of each building at a specific geographical location.
This ongoing research project was conducted by Eng. Hasan Nasrallah. Web development achieved by Kawthar Salami. The map can be accessed via the following link: <a href="http://geo.cnrs.edu.lb:8080/urbanmap/">Map</a>