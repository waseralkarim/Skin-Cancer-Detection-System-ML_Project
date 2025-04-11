# Skin Cancer Detection System - ML Project

This project focuses on building a **Skin Cancer Detection System** using machine learning techniques. The aim is to accurately classify skin lesions as benign or malignant using image-based data. This can assist in early diagnosis and support medical professionals in detecting skin cancer efficiently.

## 🔍 Problem Statement

Skin cancer is one of the most common forms of cancer worldwide. Early detection significantly improves the chances of successful treatment. This project utilizes image classification models to automate the diagnosis of skin lesions, providing a low-cost, scalable solution.

## 📂 Project Structure

Skin-Cancer-Detection-System-ML_Project
dataset/                 # Contains image data for training/testing
models/                  # Trained models and architecture
notebooks/               # Jupyter Notebooks for EDA, training, and testing
static/                  # Static files (for web interface, if any)
templates/               # HTML templates (if Flask/Django is used)
app.py                   # Main app file (Flask-based web app)
requirements.txt         # Python dependencies
README.md                # Project documentation



## 🚀 Features

- Image classification using deep learning
- Binary classification: Benign vs. Malignant
- Clean and interactive web interface (Flask-based)
- Jupyter notebooks for training and evaluation
- Preprocessing, augmentation, and model evaluation

## 🛠️ Tech Stack

- **Programming Language:** Python
- **Libraries/Frameworks:** TensorFlow / Keras, NumPy, OpenCV, Flask
- **Tools:** Jupyter Notebook, Matplotlib, Scikit-learn

## 🧠 Model Overview

- **Model Type:** Convolutional Neural Network (CNN)
- **Loss Function:** Binary Crossentropy
- **Optimizer:** Adam
- **Metrics:** Accuracy, Precision, Recall

## 🖼️ Dataset

- The dataset consists of labeled images of skin lesions.
- Images are preprocessed (resizing, normalization) before training.
- Augmentation techniques like rotation, flipping, and zoom are used to avoid overfitting.

## 💡 How to Run

1. **Clone the repository**

```bash
git clone https://github.com/Waser-Al-Karim/Skin-Cancer-Detection-System-ML_Project.git
cd Skin-Cancer-Detection-System-ML_Project
```
2. **Create and activate a virtual environment**

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

```
3. **Install dependencies**

```bash
bash
CopyEdit
pip install -r requirements.txt

```

4. **Run the app**

```bash
bash
CopyEdit
python app.py

```

Open your browser and go to `http://127.0.0.1:5000` to view the web interface.

## ✅ Future Improvements

- Support for multi-class classification
- Model optimization and hyperparameter tuning
- Deploy the model using Docker or streamlit on cloud platforms

## 🤝 Contributing

Pull requests are welcome! If you'd like to contribute, please fork the repo and submit a PR.
