# Image-Layout-Learning

Here is the official directory of the paper [Self-supervised Photographic Image Layout Representation Learning](https://arxiv.org/abs/2403.03740).

The link to the LODB dataset proposed in the paper is as follows [GoogleDrive](https://drive.google.com/file/d/1EfzI04k9TsSsOBwza-EsV0hqfLC2WuN_/view?usp=sharing). 

## Overview

LODB (Layout Object Database) is designed to address the shortcomings of existing image layout datasets, which often suffer from coarse labeling and limited diversity. LODB offers fine-grained annotations across 17 categories and includes 6029 images, providing a more detailed and comprehensive resource for evaluating layout representation algorithms.

## Key Features

- **Fine-Grained Labels**: LODB captures subtle differences in layout, including variations in element arrangement and orientation, allowing for precise evaluation of algorithms.
- **Broad Semantic Diversity**: With images sourced from multiple open datasets, LODB covers a wide range of scenes, ensuring robust performance evaluation across diverse scenarios.
- **Large-Scale Dataset**: Comprising 17 categories and thousands of images, LODB offers an expansive resource for in-depth analysis and algorithm development.

## Dataset Construction

LODB was developed in collaboration with experts in photography and painting, who selected categories based on core principles of photographic composition. Each image was rigorously classified, requiring consensus from at least three experts to ensure accuracy and reliability. We also implemented scripts to monitor and maintain semantic diversity across categories.

### Image Sources

LODB images were drawn from a variety of open datasets, including PARA, AADB, AVA-test, ADE20k, COCO2017, FLICKR-AES, TAD66k, VOC2007, and VOC2012.

## Qualitative and Quantitative Insights

LODB sets itself apart by emphasizing semantic diversity and detailed categorization. Compared to other datasets, LODB shows higher semantic variation within each category, providing richer data for algorithm testing.
