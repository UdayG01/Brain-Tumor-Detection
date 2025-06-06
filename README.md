# Brain Tumor Detection Model Comparison 🧠📊

A detailed evaluation of cutting-edge deep learning models for accurate brain tumor detection from MRI scans, empowering advancements in medical diagnostics. 🧠✨

<p align="center">
    <img src="tumor_image.webp" alt="Brain Tumor Project Logo Image">
</p>

---

## Table of Contents 📋
- 📖 [Project Description](#project-description)  
- 🔧 [Installation Instructions](#installation-instructions)  
- 💡 [Usage Guide](#usage-guide)  
- ✨ [Features](#features)  
- 🏗️ [Architecture or Design](#architecture-or-design)  
- 🛠️ [Technologies and Dependencies](#technologies-and-dependencies)  
- 🧑‍💻 [Setup for Development](#setup-for-development)  
- ❗ [Known Issues and Roadmap](#known-issues-and-roadmap)  
- 🙌 [Acknowledgments](#acknowledgments)  
- 📞 [Contact Information](#contact-information)  

---

## Project Description 📖  
This project aims to identify the best-performing model for brain tumor detection by comparing the performance of various state-of-the-art deep learning models. The models are trained and evaluated on MRI images to detect the presence of brain tumors.  

---

## Installation Instructions 🔧  
1. 🗂 Clone the repository:  
    ```bash  
    git clone https://github.com/yourusername/brain-tumor-detection.git  
    cd brain-tumor-detection  
    ```  
2. 🔴 Set up a virtual environment:  
    ```bash  
    python -m venv venv  
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`  
    ```  
3. 📦 Install the required dependencies:  
    ```bash  
    pip install -r requirements.txt  
    ```  

---

## Usage Guide 💡  
1. 📥 Download the dataset from Kaggle:  
    ```bash  
    mkdir ~/.kaggle  
    cp kaggle.json ~/.kaggle/  
    chmod 600 ~/.kaggle/kaggle.json  
    kaggle datasets download -d ahmedhamada0/brain-tumor-detection --unzip  
    ```  
2. ▶️ Run the Jupyter Notebook:  
    ```bash  
    jupyter notebook BTD_Model_Comparison.ipynb  
    ```  
3. Follow the steps in the notebook to train and evaluate the models.  

---

## Features ✨  
- 🔬 Comparison of multiple pre-trained models: **VGG19**, **InceptionV3**, **MobileNetV2**, **ResNet50**, **VGG16**, **InceptionResNetV2**.  
- 🔧 Custom CNN model implementation.  
- 📊 Data augmentation for improved model performance.  
- 📈 Evaluation metrics: Accuracy, Loss, AUC-ROC score, Confusion Matrix, Classification Report.  
- 🔽 Visualization of learning curves.  

---

## Architecture or Design 🏗️  
The project follows a structured workflow:  
1. 💂️ **Data Loading and Preprocessing**  
2. 🏗️ **Model Building and Compilation**  
3. 🔄 **Model Training**  
4. 📈 **Model Evaluation**  
5. 🔄 **Visualization of Results**

## Sample images from Dataset
<p align="center">
    <img src="https://github.com/user-attachments/assets/9e0de33b-832c-411f-ad18-fa0094d49433">
</p>

---

## Technologies and Dependencies 🛠️  
- 🔬 Python  
- ⚙️ TensorFlow  
- 🥦 Keras  
- 🔢 NumPy  
- 📑 Pandas  
- 📊 Matplotlib  
- 📚 Scikit-learn  

---

## Setup for Development 🧑‍💻  
1. 🔬 Ensure you have Python installed.  
2. 🔧 Follow the installation instructions to set up the environment.  
3. 📃 Use the provided Jupyter Notebook for development and experimentation.  

---

## Known Issues and Roadmap ❗  
### Known Issues 🚧  
- 📊 Limited dataset size may affect model performance.  
- ⚡ High computational requirements for training deep learning models.  

### Roadmap 🛏️  
- 📈 Expand the dataset for better model generalization.  
- 🧐 Implement additional models for comparison.  
- ⏩ Optimize model training for faster performance.  

---
## Results
<p align="center">
        <img src="https://github.com/user-attachments/assets/ef85ea62-eadb-4e4e-8a36-b79287fea39e">
</p>


---

## Acknowledgments 🙌  
- 🎉 Thanks to [Kaggle](https://www.kaggle.com/) for providing the dataset.  
- 💡 Inspired by various deep learning research papers and tutorials.
- [Comparison of VGG-19 and RESNET-50 Algorithms in Brain Tumor Detection](https://ieeexplore.ieee.org/document/10126451)  

---
 
Feel free to ⭐ the repository, fork it, or open issues for feedback!  

---
