# Manga Layout Analysis
This repository holds my work for the **Manga Layout Analysis via Deep Learning (SCSE01)** research project under the 2021 Nanyang Research Programme (NRP) by Nanyang Technological University.

## ⚙️ Mechanism
As of now, `Manga Layout Analysis.ipynb`:
- performs Instance Segmentation on manga pages to identify frames (panels), faces, and text (speech bubbles),
- associates faces to text, and
- determines the order of text.

`Manga OCR.ipynb` builds a Japanese Hiragana and Kanji Optical Character Recognition model using the Kuzushiji-49 and Kuzushiji-Kanji datasets.

## 🎯 Overarching Aim
Overall, this research project aims to lay the foundation for easy translation and adaptation of manga into movie scripts, novels, and other literature pieces.

## 📚 Acknowledgements
Abdulla, W. (2017). Mask R-CNN for object detection and instance segmentation on Keras and TensorFlow. GitHub. [https://github.com/matterport/Mask_RCNN](https://github.com/matterport/Mask_RCNN)

Aizawa, K., Fujimoto, A., Otsubo, A., Ogawa, T., Matsui, Y., Tsubota, K., & Ikuta, H. (2020). Building a Manga Dataset "Manga109" with Annotations for Multimedia Applications. IEEE MultiMedia, 27(2), 8–18.

Brownlee, J. (2020). How to Train an Object Detection Model with Keras. Machine Learning Mastery. [https://machinelearningmastery.com/how-to-train-an-object-detection-model-with-keras/](https://machinelearningmastery.com/how-to-train-an-object-detection-model-with-keras/)

Clanuwat, T., Bober-Irizar, M., Kitamoto, A., Lamb, A., Yamamoto, K., & Ha, D. (2018). Deep Learning for Classical Japanese Literature. [https://arxiv.org/abs/1812.01718](https://arxiv.org/abs/1812.01718)

Rosebrock, A. (2020, August 17). OCR with Keras, TensorFlow, and Deep Learning. PyImageSearch. [https://www.pyimagesearch.com/2020/08/17/ocr-with-keras-tensorflow-and-deep-learning/](https://www.pyimagesearch.com/2020/08/17/ocr-with-keras-tensorflow-and-deep-learning/)