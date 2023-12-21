# Object Detection Optimization with Segmentation and Data Augmentation on Toxic Snail Species using YOLO v8 and Roboflow

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

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
![image](https://github.com/reygaferdiansyah/Yolo8_With_Roboflow/assets/54634029/00538e77-f3dc-4a2e-ae0a-1bc0811f4c01)
Confusion matrix digunakan untuk mengevaluasi kinerja suatu model klasifikasi dengan membandingkan hasil prediksi model dengan label sebenarnya dari objek. Yang ditunjukkan pada gambar 6, terdapat 10 class siput beracun dalam confusion matrix.

![image](https://github.com/reygaferdiansyah/Yolo8_With_Roboflow/assets/54634029/17f1ad6a-8ea7-4415-84bc-dc9ef7c63d3f)
Confusion matrix normalized, juga dikenal sebagai confusion matrix yang dinormalisasi, adalah representasi confusion matrix yang menggambarkan proporsi atau persentase dari kesalahan klasifikasi dalam setiap kelas. Hal ini membantu dalam memperoleh pemahaman yang lebih baik tentang kinerja model klasifikasi dalam mengklasifikasikan berbagai kelas seperti yang ditunjukkan pada gambar 

![image](https://github.com/reygaferdiansyah/Yolo8_With_Roboflow/assets/54634029/c98f0eb4-5ce3-4518-9dc9-c236b618cc5a)

hasil dari pelatihan model sebanyak 50 epoch. model tersebut dapat digunakan untuk mendeteksi objek pada gambar atau video yang belum pernah dilihat sebelumnya. Proses deteksi objek melibatkan melewati gambar atau video melalui model YOLOv8, di mana model tersebut akan menentukan lokasi dan label kelas objek pada gambar atau video tersebut.





