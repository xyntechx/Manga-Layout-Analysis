# Manga Layout Analysis
This repository holds my work for the **Manga Layout Analysis via Deep Learning (SCSE01)** research project under the 2021 Nanyang Research Programme (NRP) by Nanyang Technological University.

## ⚙️ Mechanism
### IS[Mask R-CNN].ipynb
- Performs instance segmentation on manga to identify frames (panels), faces, and text (speech bubbles) using the Manga109 dataset
- Associates faces to text
- Determines the order of text

### IS[PointRend].ipynb
Performs instance segmentation on manga pages to identify frames (panels) and text (speech bubbles) using a custom dataset consisting of manually annotated Manga109 images using Labelme

Note: Faces are not included as they are too time-consuming to annotate manually

### M-OCR.ipynb
Builds a Japanese hiragana and kanji optical character recogniser using the Kuzushiji-49 and Kuzushiji-Kanji datasets

## 🎯 Overall Aim
- Innovate an end-to-end integrated Manga Layout Analysis system for easy adaptation of manga into anime, movies, novels, and other media
- Compare the performance (accuracy and precision) as well as training and execution time of different deep learning models for instance segmentation and optical character recognition
