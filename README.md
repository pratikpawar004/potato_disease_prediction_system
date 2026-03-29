# 🥔 Potato Disease Detection using CNN & Flask

A **Deep Learning–based web application** that detects potato leaf diseases using a **Convolutional Neural Network (CNN)** and **Transfer Learning**.
Users can upload a potato leaf image, and the system predicts whether the leaf is **Healthy**, affected by **Early Blight**, or **Late Blight**.

---

## 📌 Project Overview

Potato diseases can cause significant crop losses if not detected early.
This project leverages **TensorFlow (Keras)** to build a CNN-based image classification model and deploys it using **Flask** for real-time predictions.

The system helps in:

* Early disease detection
* Improving crop management
* Reducing agricultural losses

---

## 🚀 Features

* Upload potato leaf images via web interface
* CNN-based disease classification
* Supports three classes:

  * Potato___Healthy
  * Potato___Early_blight
  * Potato___Late_blight
* Displays uploaded image with prediction
* Shows prediction confidence score
* Simple and user-friendly UI
* Transfer Learning support for better accuracy

---

## 🧠 Technologies Used

* Python 3.10
* TensorFlow / Keras
* OpenCV
* NumPy, Pandas
* Matplotlib, Seaborn
* Flask (Web Deployment)
* HTML & CSS

---

## 📂 Project Structure

```
potato_disease_prediction_system/
│
├── dataset/
│   └── PlantVillage/
│       ├── Potato___Early_blight/
│       ├── Potato___Late_blight/
│       └── Potato___Healthy/
│
├── potenv/                     # Virtual Environment (ignored)
├── app.py                      # Flask application
├── Transfer_Learning-CNN.ipynb # Model training notebook
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 🧪 Model Details

* Model Type: Convolutional Neural Network (CNN)
* Transfer Learning: Optional
* Input Image Size: 224 × 224
* Optimizer: Adam
* Loss Function: Categorical Crossentropy
* Image Augmentation: ImageDataGenerator
* Dataset: PlantVillage Potato Leaf Dataset

---

## 📊 Dataset

Dataset used: **PlantVillage**

Classes:

* Potato Early Blight
* Potato Late Blight
* Potato Healthy

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/pratikpawar004/potato_disease_prediction_system.git
cd potato_disease_prediction_system
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv potenv
potenv\Scripts\activate   # Windows
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🚀 Usage

### ▶️ Run Jupyter Notebook (Model Training)

```bash
jupyter notebook
```

### ▶️ Run Flask Application

```bash
python app.py
```

Then open in browser:

```
http://127.0.0.1:5000
```

---

## 📸 Output

The model provides:

* Predicted Disease Type
* Confidence Score
* Uploaded Image Preview

---

## ⚠️ Notes

* Ensure correct virtual environment (`potenv`) is activated
* Install OpenCV to avoid errors:

```bash
pip install opencv-python
```

---

## 🔥 Future Improvements

* Deploy on cloud (AWS / Render / GCP)
* Build mobile application
* Improve accuracy with larger datasets
* Add multi-crop disease detection

---

## 👨‍💻 Author

**Pratik Pawar**

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
