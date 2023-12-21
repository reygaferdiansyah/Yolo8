# Object Detection Optimization with Segmentation and Data Augmentation on Toxic Snail Species using YOLO v8 and Roboflow

[![License: AGPL-3.0](https://img.shields.io/badge/License-AGPL--3.0-blue.svg)](https://opensource.org/licenses/AGPL-3.0)
![python version](https://img.shields.io/badge/python-3.6%2C3.7%2C3.8-blue?logo=python)
![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)
![Roboflow](https://raw.githubusercontent.com/roboflow-ai/notebooks/main/assets/badges/roboflow-blogpost.svg)

This project aims to optimize object detection for toxic snail species by leveraging segmentation and data augmentation techniques. The algorithm employed in this project is YOLO (You Only Look Once) version 8, with data augmentation processing obtained through Roboflow.

## Table of Contents
- [Project Description](#project-description)
- [How to Use](#how-to-use)
- [Data Augmentation](#data-augmentation)

## Project Description

This project utilizes YOLO v8 for object detection on images containing toxic snail species. The integration of segmentation and data augmentation techniques from Roboflow is aimed at enhancing the quality and accuracy of detection. The project serves as a foundational framework for object detection applications focused on specific species.

## How to Use

1. Download or clone this repository:

    ```bash
    git clone https://github.com/username/toxic-snail-object-detection.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the object detection script on images or videos:

    ```bash
    python object_detection.py --input input_image.jpg --output output_image.jpg
    ```

    Replace `input_image.jpg` with the input image file name and `output_image.jpg` with the output file name.

## Getting Started

1. **Upload your Dataset:**
    - Log in to Roboflow.
    - Create a new dataset and upload your images.

2. **Explore Roboflow Interface:**
    - Familiarize yourself with the Roboflow dashboard and project structure.

## Image Annotation

3. **Annotation Overview:**
    - Understand the importance of image annotation for training machine learning models.     

4. **Manual Annotation:**
    - Annotate objects in images using Roboflow's manual annotation tools.

5. **Automated Annotation:**
    - Explore automated annotation options provided by Roboflow.

![image](https://github.com/reygaferdiansyah/Yolo8_With_Roboflow/assets/54634029/820627c2-4cb2-4f66-94aa-4d7443773d7d)

![image](https://github.com/reygaferdiansyah/Yolo8_With_Roboflow/assets/54634029/6b28c66b-ceaf-481e-b085-10752f7f1414)

## Data Augmentation

6. **Data Augmentation Techniques:**
    - Learn various data augmentation techniques to enhance your dataset.

7. **Applying Augmentation:**
    - Apply data augmentation to your images using Roboflow.
This project leverages data augmentation from Roboflow to enrich the training dataset. To access the dataset and additional data augmentation, you can register at [Roboflow](https://roboflow.com/).

## Exporting Datasets

8. **Exporting Datasets:**
    - Export your annotated and augmented datasets in formats suitable for machine learning frameworks.

9. **Integration with Machine Learning Frameworks:**
    - Integrate your processed dataset with popular machine learning frameworks.
    - 
![image](https://github.com/reygaferdiansyah/Yolo8_With_Roboflow/assets/54634029/00538e77-f3dc-4a2e-ae0a-1bc0811f4c01)

Confusion matrix is used to evaluate the performance of a classification model by comparing the predicted results of the model with the actual label of the object. As shown in the figure, there are 10 classes of poisonous snails in the confusion matrix.

![image](https://github.com/reygaferdiansyah/Yolo8_With_Roboflow/assets/54634029/17f1ad6a-8ea7-4415-84bc-dc9ef7c63d3f)

The normalized confusion matrix, also known as the normalized confusion matrix, is a representation of the confusion matrix that describes the proportion or percentage of misclassifications within each class. This helps in gaining a better understanding of the performance of the classification model in classifying various classes as shown in the figure 

![image](https://github.com/reygaferdiansyah/Yolo8_With_Roboflow/assets/54634029/c98f0eb4-5ce3-4518-9dc9-c236b618cc5a)

As a result of training the model for 50 epochs, the model can be used to detect objects in images or videos that have never been seen before. The object detection process involves passing the image or video through the YOLOv8 model, where the model will determine the location and class label of the object in the image or video.

![1](https://github.com/reygaferdiansyah/Yolo8_With_Roboflow/assets/54634029/b6fe22a0-3da0-494f-95bc-cdffa455408c)

![3](https://github.com/reygaferdiansyah/Yolo8_With_Roboflow/assets/54634029/eac631bb-a0a7-4645-9296-f6dbde913cbc)

![2](https://github.com/reygaferdiansyah/Yolo8_With_Roboflow/assets/54634029/16f88fc4-abf6-4da5-99b8-d8d4e439eb30)

![4](https://github.com/reygaferdiansyah/Yolo8_With_Roboflow/assets/54634029/7c4265dd-8840-4336-9a26-9895188ffe15)

![5](https://github.com/reygaferdiansyah/Yolo8_With_Roboflow/assets/54634029/c6193cc7-fa20-4d12-a153-687f8842ba19)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for more details.

