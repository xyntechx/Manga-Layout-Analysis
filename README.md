# Manga Layout Analysis via Deep Learning
Manga Layout Analysis is an end-to-end system integration of deep learning instance segmentation and optical character recognition tools as a complete solution for the adaptation of manga into other media.

## 🎉 About
Written below are the details of the research project.

### Name of Researcher
Nyx Audrey Angelo Iskandar

### Title
Manga Layout Analysis via Deep Learning

### Awards
- Silver (Top 10%) & 1st for Poster Presentation @ International Conference of Young Scientists (ICYS)
- Silver (Top 10%) @ Singapore Science & Engineering Fair (SSEF)
- TBC @ Nanyang Research Programme

### Abstract
Manga Layout Analysis is an end-to-end system integration of deep learning instance segmentation and optical character recognition tools as a complete solution for the adaptation of manga into other media. An innovative unified approach, this system combines said tools into one process to contribute to document layout analysis concerning manga on which only limited research has been conducted, and aid Japanese companies adapt manga into anime and other media. Hence, this integrated system consists of deep learning instance segmentation models trained with the Manga109 dataset, and Japanese hiragana and kanji optical character recognisers trained with Kuzushiji-MNIST datasets.

Overall, the instance segmentation models for text and frames built using Mask R-CNN and PointRend achieved mAP values of 0.93 and 0.95 respectively (IoU=0.5). For text, frames, and faces, the Mask R-CNN model achieved an mAP value of 0.90 (IoU=0.5); no PointRend model was trained as time constraints were faced due to the need for manual annotations to create a compatible dataset. The ResNet-50 and ResNet-101 Japanese hiragana and kanji optical character recognisers achieved high F1 scores of 0.89 and 0.90 respectively, similar to those of the Tesseract English and state-of-the-art Japanese optical character recognisers.

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
