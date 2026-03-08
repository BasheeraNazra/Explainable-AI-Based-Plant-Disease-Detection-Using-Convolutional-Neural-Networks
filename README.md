# 🌿 Explainable AI Based Plant Disease Detection Using Convolutional Neural Networks

## 📌 Project Overview
This project uses **Convolutional Neural Networks (CNN)** to detect plant diseases from leaf images and provides prediction explanations using **Explainable AI techniques**.  
The system analyzes leaf images to identify the disease affecting the plant, enabling **early detection and better crop management** for farmers and agricultural researchers.

---

## 🎯 Objectives
- Detect plant diseases using **deep learning techniques**
- Classify plant leaf images into **healthy and diseased categories**
- Provide **visual explanations** for model predictions
- Demonstrate the application of **AI in agriculture**

---

## 🧠 Technologies Used
- Python  
- TensorFlow / Keras  
- OpenCV  
- NumPy  
- Matplotlib  
- Jupyter Notebook

## 📂 Project Structure

```
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
```

## 📓 Notebook Description

### 1️⃣ create_npy_dataset.ipynb
This notebook handles dataset preparation, including:
- Loading the dataset
- Image preprocessing
- Data normalization
- Creating the `.npy` dataset used for training

### 2️⃣ create_CNN_model.ipynb
This notebook focuses on building and training the model:
- Constructing the CNN architecture
- Training the model using the processed dataset
- Saving the trained model files

### 3️⃣ Plant_disease_prediction_ExplainableAI.ipynb
This notebook performs prediction and explanation:
- Loading the trained model
- Testing the model on new leaf images
- Generating disease predictions with explainable outputs

---

## 🖼 Demo Test Images
The **uploadimages** folder contains sample leaf images used to test the trained model.  
You can also add your own images to this folder for custom predictions.

---

## 📊 Dataset

The dataset used in this project is based on the **PlantVillage dataset** available on Kaggle.

📥 **Download Dataset**

👉 [PlantVillage Dataset (Kaggle)](https://www.kaggle.com/datasets/emmarex/plantdisease)


---

## 🤖 Trained Model

Because GitHub does not allow files larger than **100MB**, the trained model folder is stored on **Google Drive**.

📥 **Download Model Folder**

👉 [Download Model from Google Drive](https://drive.google.com/drive/folders/13rh-k6wfwycKCCqgpw3UpcgtcBYgYLJM?usp=sharing)


---

## 🤖 Trained Model Setup

After downloading the **Model folder** from Google Drive:

1. Extract the downloaded file (if it is zipped).
2. Place the **Model folder** inside the main project directory.

## Example project structure:

```
Explainable-AI-Based-Plant-Disease-Detection-Using-Convolutional-Neural-Networks
│
├── create_npy_dataset.ipynb
├── create_CNN_model.ipynb
├── Plant_disease_prediction_ExplainableAI.ipynb
│
├── Model
│   ├── myimg_data.txt.npy
│   └── myimg_label.txt.npy
├── uploadimages
│   ├── test_image1.jpg
│   ├── test_image2.jpg
│   └── test_image3.jpg
│
└── README.md
```

Once the **Model folder** is placed correctly, you can run the prediction notebook.

---

## 🚀 How to Run the Project

1️⃣ Clone the repository
```
https://github.com/BasheeraNazra/Explainable-AI-Based-Plant-Disease-Detection-Using-Convolutional-Neural-Networks.git
```
2️⃣ Install required 
```
pip install tensorflow opencv-python numpy matplotlib jupyter
```
3️⃣ Open Jupyter Notebook
```
jupyter notebook
```
4️⃣ Run the notebooks

Since the dataset has already been processed and the model has already been trained, you can directly run:
```
Plant_disease_prediction_ExplainableAI.ipynb
```

Make sure that:
- The **Model folder** is placed in the project directory  
- The **uploadimages** folder contains the test images  

---

## 🌱 Applications
- Smart agriculture systems  
- Crop disease monitoring  
- Early plant disease detection  
- AI-based farming assistance  

---

## 👩‍💻 Author
**Sheik Basheera Nazra**  
B.Sc Computer Science  
St Ann's College for Women, Hyderabad  

---

## 📜 Note
Due to GitHub storage limitations, large files such as **datasets and trained models** are hosted externally on Google Drive.
