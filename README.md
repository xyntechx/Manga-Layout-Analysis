# Manga Layout Analysis via Deep Learning
_Copyright (c) 2021-2022 Nyx Audrey Angelo Iskandar_

Manga Layout Analysis via Deep Learning is an end-to-end system integration of instance segmentation models, novel algorithms, and optical character recognisers as a complete solution for the adaptation of manga into other media.

## 🎉 About
Written below are the details of the research project.

### Name of Researcher
[Nyx Audrey Angelo Iskandar](https://github.com/xyntechx/)

### Title
Manga Layout Analysis via Deep Learning

### Awards
- Gold @ Nanyang Research Programme 2021
- Best Presenter Award @ IRC-SET 2022
- Silver & 1st for Poster Presentation @ International Conference of Young Scientists (ICYS) 2022
- Silver @ Singapore Science & Engineering Fair (SSEF) 2022

### Abstract
Manga Layout Analysis via Deep Learning is an end-to-end system integration of instance segmentation (IS) models, novel algorithms, and optical character recognisers (M-OCRs) as a complete solution for the adaptation of manga into other media. An innovative and unified approach, this system combines the aforementioned deep learning tools into one process to contribute to document layout analysis concerning manga on which only limited research has been conducted, and aid Japanese companies adapt manga into anime and other media. This integrated system hence consists of IS models trained with the Manga109 dataset, algorithms leveraging the results of the IS models to analyse and evaluate the structure and semantics of manga, and Japanese hiragana and kanji M-OCRs trained with Kuzushiji-MNIST datasets. The IS models for text and frames built using Mask R-CNN and PointRend achieved mAP values of 0.93 and 0.95 respectively (IoU=0.5); for text, frames, and faces, the Mask R-CNN model achieved an mAP value of 0.90 (IoU=0.5). The ResNet-50 and ResNet-101 M-OCRs achieved high F1 scores of 0.89 and 0.90 respectively.

## 🪜 Structure
Listed below are the files and folders located in the root directory.

### Folders
-   `Train`
-   `Validation`

### Files
-   `IS[Mask_R_CNN]-3 (Manga109)_FTA_TOD.ipynb`
-   `main.ipynb`

## 📚 Details
Outlined below are the details regarding the folders and files in the root directory.

Note: `.ipynb` files were run on Google Colaboratory using a GPU.

### Train
Source code for training of IS and M-OCR models.

-   `IS[Mask R-CNN]-3or2 (Manga109).ipynb` => `IS[Mask R-CNN]-3 (Manga109).h5` and `IS[Mask R-CNN]-2 (Manga109).h5`
-   `IS[Mask R-CNN]-2 (manual).ipynb` => `IS[Mask R-CNN]-2 (manual).h5`
-   `IS[PointRend]-2 (manual).ipynb` => `IS[PointRend]-2 (manual)`
-   `M-OCR-ResNet-50or101.ipynb` => `M-OCR-ResNet-50.h5` and `M-OCR-ResNet-101.h5`

### Validation
50 images of sample manga pages for validation of IS, FTA, and TOD.

### IS[Mask R-CNN]-3 (Manga109)\_FTA_TOD.ipynb
Source code for testing IS[Mask R-CNN]-3 (Manga109), FTA, and TOD using images from `Validation`.

### main.ipynb
Source code used during the live demonstration segment of my NRP Oral Presentation examination.
