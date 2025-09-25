# 🛡️ Web Injection Detector – GCN-based Model  
*M.Tech (Cyber Security) – Semester (II) Minor Project*  

📂 Repository: [![GitHub Repo](https://img.shields.io/badge/GitHub-Web--Injection--Detector-blue?logo=github)](https://github.com/Karthikeyan1202/Web-Injection-Detector)  

---

## ⚙️ Tech Stack  
![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)  
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)  
![PyTorch](https://img.shields.io/badge/PyTorch-Framework-red?logo=pytorch)  
![NumPy](https://img.shields.io/badge/NumPy-Matrix%20Ops-lightblue?logo=numpy)  
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-purple?logo=pandas)  

---

## 👨‍💻 Contributors
- [![GitHub](https://img.shields.io/badge/Karthikeyan1202-black?logo=github)](https://github.com/Karthikeyan1202)  
- [![GitHub](https://img.shields.io/badge/BharathRam125-black?logo=github)](https://github.com/BharathRam125)  
- [![GitHub](https://img.shields.io/badge/SaiyanSai-black?logo=github)](https://github.com/SaiyanSai)  

---

## 📖 Overview
This project implements a **Graph Convolutional Network (GCN)-based approach** for detecting **Web Injection Attacks** at the **Web Application Firewall (WAF)** level.  

By converting web payloads into **graph-based representations**, the model achieves better **pattern recognition** and detection of **obfuscated/adversarial payloads**.  

> 🛡️ Goal: Enhance **WAF security** with deep learning models that adapt beyond signature-based rules.  

---

## 🔍 Target Attacks
- 🐍 **SQL Injection (SQLi)**  
- 🌐 **Cross-Site Scripting (XSS)**  
- 💻 **Command Injection**  

---

## 🏗️ Model Architecture
📌 **Core Components**  
- 🔹 Multi-layer **Graph Convolutional Network (GCN)**  
- 🔹 **Batch Normalization** & **Dropout** for regularization  
- 🔹 Fully-connected **classification layers**  
- 🔹 **Character-level tokenization** for payload representation  

---

## 💡 Key Insights
✅ **Strengths**  
- Learns **relational patterns** between payload characters  
- Robust to **obfuscation & bypass** techniques  
- Strong detection performance on **SQL Injection**  

⚠️ **Limitations**  
- Imbalance in dataset affects **XSS & Command Injection** results  
- **Higher computation cost** vs. rule-based WAFs  
- **Lower interpretability** compared to signature-based detection  

---

## 📊 Dataset & Preprocessing
- 📦 **Base Dataset**: [![Kaggle](https://img.shields.io/badge/Kaggle-SQLi%20%26%20XSS%20Dataset-20BEFF?logo=kaggle)](https://www.kaggle.com/datasets/alextrinity/sqli-xss-dataset)  
- 📈 **Augmentations**:  
  - Benign samples → RockYou dataset  
  - Randomized queries  
  - Admin test data  

⚙️ **Pipeline**  
1️⃣ Raw payloads → Graph structures  
2️⃣ Character-level tokenization  
3️⃣ Encoded feature vectors → GCN layers  

---

## 📚 References
- [![Kaggle](https://img.shields.io/badge/Kaggle-SQLi%20%26%20XSS%20Dataset-20BEFF?logo=kaggle)](https://www.kaggle.com/datasets/alextrinity/sqli-xss-dataset)  
- [![GitHub](https://img.shields.io/badge/BharathRam125-Repo-black?logo=github)](https://github.com/BharathRam125/InjectionDetector)  
- [![GitHub](https://img.shields.io/badge/SaiyanSai-Repo-black?logo=github)](https://github.com/SaiyanSai/InjectionDetector)  

---

## 🚀 Future Work
- ⚖️ Balance dataset for **XSS & Command Injection**  
- 🔤 Incorporate **embeddings/tokenization improvements**  
- 🌍 Collect **real-world benign & malicious traffic**  
- 🔧 Optimize **hyperparameters** for hig
