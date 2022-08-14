---
title: Image-Based Query Search Engine via Deep Learning
summary: Master's thesis project
tags:
  - Deep Learning
date: '2022-07-22T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: 
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: 'https://github.com/YYao-42/Image-Search-Engine-for-Historical-Research'
url_pdf: 'https://repository.tudelft.nl/islandora/object/uuid:4a2c9c6f-b2b8-41d6-9b70-69c4f246c964?collection=education'
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides: ""`.
slides: ""
# slides: example
---

Typically, people search images by text: users enter keywords and a search engine returns relevant results. However, this pattern has limitations. An obvious drawback is that when searching in one language, users may miss results labelled in other languages. Moreover, sometimes people know little about the object in the image and thus would not know what keywords could be used to search for more information. Driven by this use case with many applications, content-based image retrieval (CBIR) has recently been put under the spotlight, which aims to retrieve similar images in the database solely by the content of the query image without relying on textual information.

To achieve this objective, an essential part is that the search engine should be able to interpret images at a higher level instead of treating them simply as arrays of pixel values. In practice, this is done by extracting distinguishable features. Many effective algorithms have been proposed, from traditional handcrafted features to more recent deep learning methods. Good features may lead to good retrieval performance, but the problem is still not fully solved. To make the engine useful in real-world applications, retrieval efficiency is also an important factor to consider while has not received as much attention as feature extraction.

In this work, we focus on retrieval efficiency and provide a solution for real-time CBIR in million-scale databases. The feature vectors of database images are extracted and stored offline. During the online procedure, such feature vectors of query images are also extracted and then compared with database vectors, finding the nearest neighbours and returning the corresponding images as results. Since feature extraction only performs once for each query, the main limiting factor of retrieval efficiency in large-scale database is the time of finding nearest neighbours. Exact search has been shown to be far from adequate, and thus approximate nearest neighbour (ANN) search methods have been proposed, which mainly fall into two categories: compression-based and tree/graph-based. However, these two types of approaches are usually not discussed and compared together. Also, the possibility of combining them has not been fully studied. Our study (1) applies and compares methods in both categories, (2) reveals the gap between toy examples and real applications, and (3) explores how to get the best of both worlds. Moreover, a prototype of our image search engine with GUI is available on https://github.com/YYao-42/ImgSearch.
