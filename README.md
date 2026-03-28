# 🥔 Potato Disease Prediction System

A deep learning-based project that detects potato leaf diseases using Convolutional Neural Networks (CNN) and Transfer Learning.

---

## 📌 Project Overview

This project uses image classification to identify potato plant diseases such as:

* Early Blight
* Late Blight
* Healthy Leaves

The model is trained on the **PlantVillage dataset** and helps in early disease detection for better crop management.

---

## 🧠 Technologies Used

* Python 3.10
* TensorFlow / Keras
* OpenCV
* NumPy, Pandas
* Matplotlib, Seaborn
* Flask (for deployment)

---

## 📂 Project Structure

```
potato_disease_prediction_system/
│
├── dataset/
│   └── PlantVillage/
│       ├── Potato___Early_blight/
│       ├── Potato___Late_blight/
│       └── Potato___healthy/
│
├── potenv/                # Virtual Environment (ignored)
├── app.py                 # Flask app
├── Transfer_Learning-CNN imp.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

### 1. Clone the repository

```
git clone https://github.com/pratikpawar004/potato_disease_prediction_system.git
cd potato_disease_prediction_system
```

### 2. Create virtual environment

```
python -m venv potenv
potenv\Scripts\activate   # Windows
```

### 3. Install dependencies

```
pip install -r requirements.txt
```

---

## 🚀 Usage

### ▶️ Run Jupyter Notebook

```
jupyter notebook
```

### ▶️ Run Flask App

```
python app.py
```

---

## 🧪 Model Details

* CNN-based architecture
* Transfer Learning (optional)
* Image augmentation using `ImageDataGenerator`
* Input size: 224x224 (recommended)

---

## 📊 Dataset

Dataset used: **PlantVillage**

Classes:

* Potato Early Blight
* Potato Late Blight
* Potato Healthy

---

## 📸 Sample Output

The model predicts:

* Disease Type
* Confidence Score

---

## 🔥 Features

* Image classification using deep learning
* Transfer learning support
* Flask web integration
* Easy to extend for other crops

---

## ⚠️ Notes

* Make sure correct Python environment (`potenv`) is selected
* Install OpenCV (`opencv-python`) to avoid cv2 errors

---

## 🙌 Future Improvements

* Deploy on cloud (Render / AWS)
* Add mobile app interface
* Improve model accuracy with more data

---

## 👨‍💻 Author

**Pratik Pawar**

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
