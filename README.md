🌿 Explainable-AI-Based-Plant-Disease-Detection-Using-Convolutional-Neural-Networks
📌 Project Overview

This project focuses on detecting plant diseases using Convolutional Neural Networks (CNN) and providing explanations for predictions using Explainable AI techniques. The system analyzes images of plant leaves and predicts the disease affecting the plant.

The project helps in early detection of plant diseases, which can support farmers and agricultural researchers in preventing crop damage and improving agricultural productivity.

🎯 Objectives

Detect plant diseases using deep learning techniques

Classify plant leaf images into healthy or diseased categories

Provide visual explanations for predictions using Explainable AI

Demonstrate the application of AI in agriculture

🧠 Technologies Used

Python

TensorFlow / Keras

OpenCV

NumPy

Matplotlib

Jupyter Notebook

## 📂 Project Structure
'''
 Explainable-AI-Based-Plant-Disease-Detection-Using-Convolutional-Neural-Networks
 │
 ├── create_npy_dataset.ipynb
 ├── create_CNN_model.ipynb
 ├── Plant_disease_prediction_ExplainableAI.ipynb
 │
 ├── uploadimages
 │   ├── test_image1.jpg
 │   ├── test_image2.jpg
 │   └── test_image3.jpg
 │
 └── README.md
'''
📓 Notebook Description
1️⃣ create_npy_dataset.ipynb

This notebook performs:

Loading the dataset

Image preprocessing

Data normalization

Preparing the dataset for model training

2️⃣ create_CNN_model.ipynb

This notebook performs:

Building the CNN model architecture

Training the model using the processed dataset

Saving the trained model files

3️⃣ Plant_disease_prediction_ExplainableAI.ipynb

This notebook performs:

Loading the trained model

Testing the model on new leaf images

Generating predictions and explainable outputs

🖼 Demo Test Images

The uploadimages folder contains sample leaf images used for testing the trained model.

You can also add your own leaf images in this folder to test predictions.

📊 Dataset

The dataset used in this project is based on the PlantVillage dataset, which contains images of healthy and diseased plant leaves.

The dataset used in this project is available on Kaggle.

📥 Download Dataset

👉 https://www.kaggle.com/datasets/emmarex/plantdisease

🤖 Trained Model

Because GitHub does not allow files larger than 100MB, the trained model folder is stored in Google Drive.

📥 Download Model Folder

👉 https://drive.google.com/drive/folders/13rh-k6wfwycKCCqgpw3UpcgtcBYgYLJM?usp=sharing

After downloading the model folder:

Extract the downloaded folder (if it is zipped).

Place the Model folder inside the main project directory.

Example:

Explainable-AI-Based-Plant-Disease-Detection-Using-Convolutional-Neural-Networks
│
├── Model
│   └── model files
│
├── data_preprocessing.ipynb
├── model_training.ipynb
├── prediction_and_explainability.ipynb

Once the Model folder is placed correctly, you can run the prediction notebook.

🚀 How to Run the Project
1️⃣ Clone the repository

2️⃣ Install required libraries
pip install tensorflow opencv-python numpy matplotlib jupyter
3️⃣ Open Jupyter Notebook
jupyter notebook
4️⃣ Run the notebooks

Since the dataset has already been processed and the model has already been trained, you can directly run:

prediction_and_explainability.ipynb

Make sure that:

The Model folder is placed in the project directory

The uploadimages folder contains the test images

🌱 Applications

Smart agriculture systems

Crop disease monitoring

Early disease detection

AI-based farming assistance

👩‍💻 Author

Sheik Basheera Nazra
B.Sc Computer Science
St Ann's College for Women
Hyderabad

📜 Note

Due to GitHub storage limitations, large files such as datasets and trained models are hosted externally on Google Drive.
