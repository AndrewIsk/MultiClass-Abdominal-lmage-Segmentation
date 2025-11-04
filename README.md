### **Abdominal Image Segmentation**
## **Overview**

This project performs abdominal organ segmentation from CT images using a deep learning approach built in TensorFlow/Keras.
The notebook demonstrates the full workflow — from loading and preprocessing medical images to training an encoder-decoder network and visualizing segmentation results.

# **Project Structure**

**Import Libraries** – Loads required dependencies such as tensorflow, keras, numpy, matplotlib, and PIL.

**Import Images** – Loads CT images and their corresponding annotation masks from a directory.

**Resize & Preprocess** – Standardizes image sizes, converts masks to categorical labels, and normalizes pixel values for neural network input.

**Encoder/Decoder Network** – Implements a U-Net Style Architecture using a ResNet50 backbone for feature extraction.

**Prediction & Visualization** – Runs inference on test images and visualizes:

  - The original ultrasound or CT slice

  - Ground truth segmentation

  - Predicted segmentation map

**Dataset**

Publically Available Dataset on Kaggle: https://www.kaggle.com/datasets/ignaciorlando/ussimandsegm
