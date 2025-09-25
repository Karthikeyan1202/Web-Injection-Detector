# 🛡️ Web Injection Detector – GCN-based Model  
*M.Tech (Cyber Security) – Semester (II) Minor Project*  

[![GitHub Repo stars](https://img.shields.io/github/stars/Karthikeyan1202/Web-Injection-Detector?style=flat&logo=github)](https://github.com/Karthikeyan1202/Web-Injection-Detector/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Karthikeyan1202/Web-Injection-Detector?style=flat&logo=github)](https://github.com/Karthikeyan1202/Web-Injection-Detector/network/members)
[![GitHub issues](https://img.shields.io/github/issues/Karthikeyan1202/Web-Injection-Detector?logo=github)](https://github.com/Karthikeyan1202/Web-Injection-Detector/issues)
![License](https://img.shields.io/badge/License-MIT-green?logo=open-source-initiative)
![Last Commit](https://img.shields.io/github/last-commit/Karthikeyan1202/Web-Injection-Detector?logo=git&color=yellow)

---

## ⚙️ Tech Stack  
![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)  
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)  
![PyTorch](https://img.shields.io/badge/PyTorch-Framework-red?logo=pytorch)  
![NumPy](https://img.shields.io/badge/NumPy-Data%20Ops-lightblue?logo=numpy)  
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-purple?logo=pandas)  

📊 **Languages Used**  
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-98.5%25-orange?logo=jupyter)  
![Python](https://img.shields.io/badge/Python-1.2%25-blue?logo=python)  
![Other](https://img.shields.io/badge/Other-0.3%25-lightgrey)  

---

## 👨‍💻 Contributors
- [![GitHub](https://img.shields.io/badge/Karthikeyan1202-black?logo=github)](https://github.com/Karthikeyan1202)  
- [![GitHub](https://img.shields.io/badge/BharathRam125-black?logo=github)](https://github.com/BharathRam125)  
- [![GitHub](https://img.shields.io/badge/SaiyanSai-black?logo=github)](https://github.com/SaiyanSai)  

---

## 📖 Overview
This project implements a **Graph Convolutional Network (GCN)-based approach** for detecting **Web Injection Attacks** at the **Web Application Firewall (WAF)** level.  

By converting web payloads into **graph-based representations**, the model achieves superior **pattern recognition** and detection of **obfuscated/adversarial payloads**.  

> 🛡️ **Goal**: Strengthen WAFs using **deep learning** beyond traditional signature-based rules.  

---

## 🎯 Target Attacks
- 🐍 **SQL Injection (SQLi)**  
- 🌐 **Cross-Site Scripting (XSS)**  
- 💻 **Command Injection**  

---

## 🏗️ Model Architecture
📌 **Key Components**  
- 🔹 Multi-layer **Graph Convolutional Network (GCN)**  
- 🔹 **Batch Normalization** & **Dropout**  
- 🔹 Fully-connected **classification layers**  
- 🔹 **Character-level tokenization**  

📷 *(Insert Architecture Diagram here)*  
`![Model Architecture](assets/model-architecture.png)`  

---

## 💡 Key Insights
✅ **Strengths**  
- Learns **relational patterns** in payloads  
- Resistant to **obfuscation & bypass**  
- Excellent detection of **SQL Injection**  

⚠️ **Limitations**  
- Dataset imbalance → weaker for **XSS & Command Injection**  
- **Higher compute** vs rule-based detection  
- Lower **interpretability** than signature-based WAFs  

---

## 📊 Dataset & Preprocessing
- 📦 **Dataset**: [![Kaggle](https://img.shields.io/badge/Kaggle-SQLi%20%26%20XSS%20Dataset-20BEFF?logo=kaggle)](https://www.kaggle.com/datasets/alextrinity/sqli-xss-dataset)  
- 📈 **Augmentations**:  
  - RockYou benign samples  
  - Randomized queries  
  - Admin test data  

🔄 **Pipeline**  
1️⃣ Raw payloads → Graphs  
2️⃣ Character-level tokenization  
3️⃣ Encoded → GCN processing  

---

## 📚 References
- [![Kaggle](https://img.shields.io/badge/Kaggle-SQLi%20%26%20XSS%20Dataset-20BEFF?logo=kaggle)](https://www.kaggle.com/datasets/alextrinity/sqli-xss-dataset)  
- [![GitHub](https://img.shields.io/badge/BharathRam125-Repo-black?logo=github)](https://github.com/BharathRam125/InjectionDetector)  
- [![GitHub](https://img.shields.io/badge/SaiyanSai-Repo-black?logo=github)](https://github.com/SaiyanSai/InjectionDetector)  

---

## 🚀 Future Work
- ⚖️ Balance **XSS & Command Injection** datasets  
- 🔤 Explore **embeddings** for richer tokenization  
- 🌍 Collect **real-world malicious/benign traffic**  
- 🔧 Tune **hyperparameters** for peak accuracy  
- 🛡️ Deploy in **production WAF pipelines**  

---

## 📌 Project Status
✅ Completed – **M.Tech Semester II Minor Project**  
🌐 Domain: **Web Security – Injection Attack Detection**  
