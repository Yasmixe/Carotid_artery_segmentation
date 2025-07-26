# 🧠 Carotid Artery Segmentation using U-Net

This repository presents a deep learning approach for **carotid artery segmentation** from ultrasound images using a **U-Net architecture**. Carotid artery segmentation plays a vital role in diagnosing and monitoring cardiovascular diseases by helping clinicians identify plaques and measure blood flow accurately.


For this project I will be using the **Carotid Ultrasound Images** dataset, which contains a total of **2200 high-quality ultrasound images**. The images were taken from **11 different subjects**, with each person examined at least once on the left and right sides.

You can access the dataset here: [Carotid Ultrasound Image Segmentation - Kaggle](https://www.kaggle.com/datasets/orvile/carotid-ultrasound-images?resource=download)


The dataset includes the following two main folders:

- US images: 100 ultrasound images taken from each subject (1100 images in total).
- Expert mask images: Corresponding mask images created by technicians and verified by experts (1100 images in total). These masks are highly valuable for carotid artery segmentation.

## 🚀 Features

- Preprocessing of ultrasound images
- U-Net model implementation using TensorFlow/Keras
- Training and validation with performance metrics
- Visualizations of predictions vs. ground truth

## 🧪 Technologies Used

- Python 3
- TensorFlow & Keras
- NumPy & Matplotlib
- OpenCV (for image preprocessing)


## 🧰 How to Run

1. Clone the repository

```bash
git clone https://github.com/Yasmixe/Carotid_artery_segmentation.git
cd carotid-artery-segmentation

```
## Results 
The notebook includes:
- Training and validation loss plots
- IoU and Dice score computation
- Segmentation visualizations for evaluation


  
