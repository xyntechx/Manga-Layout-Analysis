# Manga Layout Analysis
This repository holds my work for the **Manga Layout Analysis via Deep Learning (SCSE01)** research project under the 2021 Nanyang Research Programme (NRP) by Nanyang Technological University.

## ⚙️ Mechanism
### MLA Mask R-CNN.ipynb [MAIN]
- Performs Instance Segmentation on manga pages to identify frames (panels), faces, and text (speech bubbles) using the Manga109 dataset
- Associates faces to text
- Determines the order of text

### MLA PointRend.ipynb
Performs Instance Segmentation on manga pages to identify frames (panels) and text (speech bubbles) using a custom dataset consisting of manually annotated Manga109 images using Labelme

Note: Faces are not included as they are too time-consuming to annotate manually

### Manga OCR.ipynb
Builds a Japanese Hiragana and Kanji Optical Character Recognition model using the Kuzushiji-49 and Kuzushiji-Kanji datasets

## 🎯 Overarching Aim
Overall, this research project aims to:
- Provide an end-to-end system integration for easy adaptation of manga into movie scripts, novels, and other literature pieces
- Compare the performance and accuracy of the different MLA models
