# Study Case : IRM analyse with U-NET

By : Julie DANIEL and Chloé GATTINO 

#### Overview
This project aims to develop a model for segmenting brain tumors from MRI images using the U-Net architecture. The goal is to assist radiologists in diagnosing and monitoring brain tumors more effectively by automating the segmentation process.

#### Project Objective
The objective of this project is to develop a deep learning model that accurately segments tumors from MRI images using the U-Net architecture. This model aims to improve the efficiency and accuracy of radiologists in diagnosing and monitoring brain tumors.

#### Dataset
The dataset used in this project consists of brain MRI scans along with manually annotated masks indicating the tumor regions. 
The dataset can be found here.

https://github.com/SartajBhuvaji/Brain-Tumor-Classification-DataSet/tree/master

#### Preprocessing
Images are resized to 256x256 pixels.
Images are normalized to enhance model training efficiency.
Masks are generated to indicate the presence of tumors.


#### Project Packages
pip install numpy
pip install tensorflow
pip install matplotlib
pip install scikit-learn


