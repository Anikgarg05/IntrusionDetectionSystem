# 🛡️ Intrusion Detection System using Machine Learning

## 📌 Project Overview

This project implements a Machine Learning based Intrusion Detection System (IDS) using the NSL-KDD dataset. The objective is to classify network traffic into different attack categories and compare the performance of multiple machine learning algorithms.

The project includes complete data preprocessing, feature engineering, model training, evaluation, and visualization.

---

## 🚀 Features

- Data Cleaning and Preprocessing
- Attack Category Classification
- Label Encoding
- Min-Max Feature Scaling
- Model Comparison
- Confusion Matrix Visualization
- Feature Importance Analysis
- Accuracy Comparison Graph

---

## 📂 Dataset

Dataset Used:
- NSL-KDD Dataset

---

## 🏷 Attack Categories

The project classifies attacks into:

- Normal
- DoS (Denial of Service)
- Probe
- R2L (Remote to Local)
- U2R (User to Root)
- Other

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🤖 Machine Learning Models

The following algorithms were implemented and compared:

- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes

---

## 📊 Model Performance

| Model | Accuracy |
|--------|----------|
| Random Forest | **98.76%** ✅ |
| Decision Tree | 98.45% |
| KNN | 97.65% |
| SVM | 95.83% |
| Naive Bayes | 34.42% |

Random Forest achieved the highest classification accuracy.

---

## 📈 Visualizations

The notebook includes:

- Attack Distribution
- Model Accuracy Comparison
- Confusion Matrix
- Feature Importance Graph

---

## 📁 Project Structure

```
IntrusionDetectionSystem/
│
├── intrusion_detection.ipynb
├── README.md
├── requirements.txt
├── images/
│   ├── attack_distribution.png
│   ├── confusion_matrix.png
│   ├── feature_importance.png
│   └── model_accuracy.png
└── dataset_link.txt
```

---

## ⚙ Installation

Clone the repository

```bash
git clone https://github.com/Anikgarg05/IntrusionDetectionSystem.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run

```bash
jupyter notebook intrusion_detection.ipynb
```

---

## 📦 Required Libraries

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
```

---

## 📌 Future Improvements

- Deep Learning (ANN)
- CNN for Intrusion Detection
- LSTM Based IDS
- XGBoost
- LightGBM
- Real-Time Network Packet Detection
- Deployment using Flask
- REST API Integration

---

## 🎯 Learning Outcomes

- Data Preprocessing
- Feature Engineering
- Multi-Class Classification
- Model Evaluation
- Confusion Matrix Analysis
- Feature Importance Analysis
- Machine Learning Workflow

---

## 👨‍💻 Author

Anik Garg

B.Tech Computer Science Engineering (IoT)

Manipal University Jaipur

GitHub: https://github.com/Anikgarg05/IntrusionDetectionSystem.git

---

⭐ If you found this project useful, don't forget to star the repository!
