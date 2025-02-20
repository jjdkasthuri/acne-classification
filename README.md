# Acne Classification with Deep Learning
All packages and dependencies are included in the requirements.txt.

Python Version
3.7
# Introduction
Without a doubt, most of teenages face acne problem. However, there isn't a guideline on how serious the acne is and what proper steps should be taken in order to cure the acne and prevent scars. Hence, acne classification is developed using deep learning. It is carried out using Resnet-18 model in this project. It is able to classify acne seriousness into:

Normal
Level 0
Level 1
Level 2
as shown below:


# Dataset
250 HD images were being hand-picked for each classes from various internet sources.


# Annotation
Data annotation is being carried out by separating dataset into 4 classes.


# Data Preprocessing
To increase the size of the dataset for training, data preprocessing is being carried out which includes:

Flip: Horizontal, Vertical
90° Rotate: Clockwise, Counter-Clockwise, Upside Down
Crop: 0% Minimum Zoom, 50% Maximum Zoom
Rotation: Between -15° and +15°
Blur: Up to 10px
Rotate: 30 degree
Installling Requirements
pip install -r requirements.txt
Run the code
streamlit run main.py
Results of AI Model
The AI Model is able to achieve up to 90% accuracy by training with only 250 HD images from each classes.


		
