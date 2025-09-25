# 🛡️ Web Injection Detector – GCN-based Model  
*M.Tech (Cyber Security) – Semester (II) Minor Project*  

📂 Repository: [![GitHub Repo](https://img.shields.io/badge/GitHub-Web--Injection--Detector-blue?logo=github)](https://github.com/Karthikeyan1202/Web-Injection-Detector)  

---

## 👨‍💻 Contributors
- [![GitHub](https://img.shields.io/badge/Karthikeyan1202-black?logo=github)](https://github.com/Karthikeyan1202)  
- [![GitHub](https://img.shields.io/badge/BharathRam125-black?logo=github)](https://github.com/BharathRam125)  
- [![GitHub](https://img.shields.io/badge/SaiyanSai-black?logo=github)](https://github.com/SaiyanSai)  

---

## 📖 Overview
This project implements a **Graph Convolutional Network (GCN)-based approach** for detecting **Web Injection Attacks** at the Web Application Firewall (WAF) level.  

By converting web payloads into **graph-based representations**, the system enables enhanced **pattern recognition** and improved detection of **obfuscated or adversarial attack payloads**.  

**🔍 Target Attacks**
- 🐍 SQL Injection (SQLi)  
- 🌐 Cross-Site Scripting (XSS)  
- 💻 Command Injection  

---

## 🏗️ Model Architecture
- 🔹 Multi-layer Graph Convolutional Network (GCN)  
- 🔹 Batch Normalization & Dropout regularization  
- 🔹 Fully connected classification layers  
- 🔹 Character-level tokenization for input representation  

---

## 💡 Key Insights
**✅ Strengths**
- Learns relational patterns between payload characters  
- Effective against obfuscation & bypass techniques  
- Strong detection performance on SQL Injection  

**⚠️ Limitations**
- Performance imbalance on XSS & Command Injection due to dataset skew  
- Computationally more expensive than rule-based detection  
- Interpretability challenges vs signature-based WAF rules  

---

## 📊 Dataset & Preprocessing
- 📦 **Base Dataset**: [![Kaggle](https://img.shields.io/badge/Kaggle-SQLi%20%26%20XSS%20Dataset-20BEFF?logo=kaggle)](https://www.kaggle.com/datasets/alextrinity/sqli-xss-dataset)  
- 📈 **Augmentations**: Added benign samples (RockYou dataset, randomized queries, admin test data)  
- ⚙️ **Pipeline**:  
  1. Raw payloads → Graph structures  
  2. Character-level tokenization  
  3. Encoded vectors optimized for GCN  

---

## 📚 References
- [![Kaggle](https://img.shields.io/badge/Kaggle-SQLi%20%26%20XSS%20Dataset-20BEFF?logo=kaggle)](https://www.kaggle.com/datasets/alextrinity/sqli-xss-dataset)  
- [![GitHub](https://img.shields.io/badge/BharathRam125-Repo-black?logo=github)](https://github.com/BharathRam125/InjectionDetector)  
- [![GitHub](https://img.shields.io/badge/SaiyanSai-Repo-black?logo=github)](https://github.com/SaiyanSai/InjectionDetector)  

---

## 🚀 Future Work
- ⚖️ Handle dataset imbalance for XSS & Command Injection  
- 🔤 Explore embeddings for tokenization  
- 🌍 Collect & integrate real-world traffic  
- 🔧 Optimize hyperparameters for accuracy  
- 🛡️ Deploy in real-time WAF pipelines  

---

## 📌 Project Status
✅ Completed as **M.Tech Semester II Minor Project**  
🌐 Domain: Web Security – Injection Attack Detection  
