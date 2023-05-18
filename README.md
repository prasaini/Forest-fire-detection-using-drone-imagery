# Forest-fire-detection-using-drone-imagery
This project aims to detect forest fires using drone imagery. The process involves data preprocessing and the implementation of a deep learning model for accurate detection. The project utilizes two main files: PREPROCESSING.ipynb and Forest fire detection.ipynb.

## Files
### 1. PREPROCESSING.ipynb
This Jupyter Notebook file handles the data preprocessing stage. The data is divided into two classes: "fire and smoke" or "no fire and no smoke". The purpose of this file is to prepare the data for training the forest fire detection model. Here are some key details about this file:

Total number of training images: 12,000
Total number of test images: 500
Class names: "fire and smoke" or "no fire and no smoke"
The preprocessing step is essential to ensure the data is properly formatted and organized for training the model.

### 2. Forest fire detection.ipynb
This Jupyter Notebook file contains the implementation of the forest fire detection project. It is written in the Python programming language. The file utilizes the *EfficientNetV2B3* model for accurate detection of forest fires. The following libraries are used in this project:

NumPy: A library for efficient numerical operations in Python.  
Pandas: A data manipulation and analysis library.  
TensorFlow: An open-source machine learning framework.  
Scikit-learn (sklearn): A machine learning library for various tasks.  
The model trained using this project achieves an accuracy of 100% in detecting forest fires. This high accuracy indicates the effectiveness of the implemented model in distinguishing between fire and smoke and the absence of fire and smoke.
## 3. Dataset
FLAME 2: FIRE DETECTION AND MODELING: AERIAL MULTI-SPECTRAL IMAGE DATASET   
Source - IEEE DataPort
## Usage
To use this project, follow these steps:

Execute the PREPROCESSING.ipynb file to preprocess the data. This step ensures the data is properly prepared for training the model.
Run the Forest fire detection.ipynb file to implement the forest fire detection project. This file contains the model implementation and achieves an accuracy of 100%.
Make sure to install the required libraries mentioned above before executing the code.

## Conclusion
The Forest Fire Detection using Drone Imagery project provides an effective solution for detecting forest fires. By utilizing drone imagery and a deep learning model, it achieves accurate classification between fire and smoke and the absence of fire and smoke. This project can be used as a valuable tool for early detection and prevention of forest fires, contributing to the preservation of natural resources and the safety of affected areas.




