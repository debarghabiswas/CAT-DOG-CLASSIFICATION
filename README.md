## Project Overview

The goal of this project is to build a deep learning model capable of classifying images as either **cats** or **dogs**. To achieve this, I utilized the **ResNet50** architecture as the base model for feature extraction, followed by two custom **Dense layers** for the classification task.

The entire training process was performed on a **CPU-only** environment (no GPU acceleration), which took approximately **3 to 4 hours** to complete. Despite the hardware limitation, the model successfully achieved an accuracy of **96%** on the validation set.

## Dataset

You can download the dataset used for training and validation from this [Google Drive link](https://sds.courses/cm/dl-az-completeDatasets) provided by the SuperDataScience Deep Learning course.

## Resources and Framework

* **Dataset Source**: SuperDataScience Deep Learning Course
* **Base Model**: ResNet50
* **Framework Used**: TensorFlow
