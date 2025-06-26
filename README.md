# 📡 Network Slicing Classification – Telecom ML Demo

This project explores machine learning techniques to classify different types of **network slice configurations** in a 5G environment. It demonstrates how supervised ML can assist in making proactive, intelligent decisions for dynamic traffic management based on features such as packet delay, bit rate, and application use.

---

## 🎯 Objective
To train a classification model that can predict the most appropriate **network slice configuration** based on features like delay, packet loss, traffic source (IoT, public safety, healthcare, etc.), and device/application context.

This task simulates a **real-world scenario** where network slicing decisions must be made automatically, even in the presence of potential network failures.

---

## 📊 Dataset
- 📌 **Source**: Kaggle — [Network Slicing Recognition Dataset](https://www.kaggle.com/datasets/gauravduttakiit/network-slicing-recognition)
- 💾 Features:
  - **Packet Delay**
  - **Packet Loss Rate**
  - **Guaranteed Bit Rate (GBR)**
  - **LTE/5G Equipment Categories**
  - Binary indicators for usage in:
    - Healthcare
    - Public Safety
    - Smart City & Transportation
    - Industry 4.0
    - Smartphones
    - IoT Devices

- 🎯 **Target**: `Slice Type` – category representing the network configuration allocated for the connection (actual class labels are encoded integers)

---

## 🔬 Techniques Used
- Exploratory Data Analysis (EDA)
- Feature Encoding
- Supervised Classification
- Train/Test Splitting
- Model Evaluation (Accuracy, log-loss, ROC AUC)

---

## 📈 Tools & Libraries
- Python 3.10+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## 🧪 Results
- Accuracy: **56.7%** (Decision Tree Classifier)
- Top features based on model importance:
  - Smart Transportation
  - Healthcare
  - AR/VR/Gaming

---

## 🚀 How to Run
1. Clone this repository
2. Install dependencies:
pip install -r requirements.txt
3. Run the notebook:
jupyter notebook network_slicing_classification.ipynb

---

## 👩‍💻 Author
**Leen Alkhouri**  
MSc Computer Science | Ex-Telecom Engineer | Exploring ML in Network Systems  
[LinkedIn](linkedin.com/in/leen-alkhouri-333b42208/) | [GitHub](github.com/Leenkh3)

---

## 💬 Notes
This notebook is part of my learning journey into applied machine learning for telecommunications. I welcome feedback, collaborations, or mentorship from anyone working at the intersection of AI and 5G networks.
