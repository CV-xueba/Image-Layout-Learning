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


## LODB Layout Categories and Abbreviations

The LODB dataset encompasses 17 distinct image layout categories, each represented by an abbreviation for easy reference. Below is a summary of the abbreviations, their corresponding layout classes, and the number of images available for each category:

- **Cent. (Rule of Center)**: This category includes images where the main subject is centered within the frame. **947** images are available.

- **RoT.L (Rule of Three - Left)**: Images where the main subject is aligned with the left vertical third of the frame. **214** images are available.

- **RoT.R (Rule of Three - Right)**: Similar to RoT.L, but with the subject aligned with the right vertical third. **275** images are available.

- **O2Dia.L (Two Objects Diagonal - Left)**: This category contains images with two objects aligned diagonally from the top-left corner. **301** images are available.

- **O2Dia.R (Two Objects Diagonal - Right)**: Similar to O2Dia.L, but with the diagonal alignment from the top-right corner. **293** images are available.

- **O2Hor. (Horizontal Layout for Two Objects)**: Images where two objects are placed in a horizontal alignment. **386** images are available.

- **O3Li. (Three Objects on the Same Line)**: This category includes images where three objects are aligned horizontally. **157** images are available.

- **O3Tri. (Triangle Layout - Three Objects)**: Images where three objects form a triangular layout. **115** images are available.

- **Oline. (More than Three Objects on a Line)**: This category contains images with more than three objects arranged in a straight line. **110** images are available.

- **Pat. (Image Full of Patterns)**: Images that primarily consist of repeating patterns. **255** images are available.

- **DiaL. (Diagonal Structure - Left)**: Images where the composition follows a diagonal structure from the top-left corner. **446** images are available.

- **DiaR. (Diagonal Structure - Right)**: Similar to DiaL, but with the diagonal structure from the top-right corner. **236** images are available.

- **Hor. (Horizontal Structure)**: This category includes images where the composition is horizontally structured. **574** images are available.

- **Tri. (Triangle Structure)**: Images where the layout follows a triangular structure. **451** images are available.

- **Ver. (Vertical Structure)**: This category contains images with a vertical composition. **455** images are available.

- **Radi. (Radial Structure)**: Images where the composition radiates outward from a central point. **187** images are available.

- **DiaX. (Bi-Diagonal Structure)**: This category includes images with a bi-diagonal structure, where the composition follows both diagonal lines. **861** images are available.

## Qualitative and Quantitative Insights

LODB sets itself apart by emphasizing semantic diversity and detailed categorization. Compared to other datasets, LODB shows higher semantic variation within each category, providing richer data for algorithm testing.
