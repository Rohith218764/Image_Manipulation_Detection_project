📌 Project Overview

This project focuses on detecting whether a digital image has been manipulated or not. With the increasing use of image editing tools, forged images can easily spread misinformation. This system uses Error Level Analysis (ELA) combined with a Convolutional Neural Network (CNN) to identify inconsistencies caused by image tampering.

🎯 Objectives

Detect forged or manipulated images automatically

Use ELA to highlight compression inconsistencies

Train a CNN model to classify images as authentic or manipulated

Achieve reliable accuracy using deep learning techniques

🛠 Tech Stack

Python, TensorFlow, Keras, OpenCV, NumPy, Pandas, Matplotlib, scikit-learn, CNN, Error Level Analysis (ELA), Jupyter Notebook

⚙️ Methodology

Input image is taken from the dataset

Image is recompressed and Error Level Analysis is applied

The ELA image is preprocessed and fed into the CNN

CNN learns patterns of compression artifacts and noise inconsistencies

The model predicts whether the image is real or manipulated

📊 Dataset

The model is trained and tested using a publicly available image forgery dataset (such as CASIA2 from Kaggle). The dataset contains both original and manipulated images.

📈 Results

The model achieved approximately 85% accuracy in detecting manipulated images.
It successfully identifies splicing and copy-move forgeries by learning subtle compression patterns.
