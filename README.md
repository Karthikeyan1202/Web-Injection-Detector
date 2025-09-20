# 🛡️ Web Injection Detector – GCN-based Model  
📌 M.Tech (Cyber Security) – Semester II Minor Project  
🔗 Repository: [Web-Injection-Detector](https://github.com/Karthikeyan1202/Web-Injection-Detector)  

---

## 📌 Overview  
A **Graph Convolutional Network (GCN)-based system** for detecting **Web Injection Attacks** at the **Web Application Firewall (WAF)** level.  
By structuring web request payloads into **graph-based representations**, the model enhances **pattern recognition and anomaly detection**.  

⚠️ **Disclaimer**  
- 🚧 This model is still under development  
- 🗂️ Dataset used is a **test dataset** and may not cover all real-world cases  
- 🛑 Focused only on **SQL Injection, XSS, and Command Injection**  
- ⚠ Dataset imbalance detected → needs more **XSS & command injection samples**  

---

## 🏗️ Model Architecture  
✨ The detection engine is powered by a **GCN (Graph Convolutional Network)** with:  
- 🔹 **3-layer GCN** for feature extraction  
- 🔹 **Batch Normalization & Dropout** for regularization  
- 🔹 **Fully Connected Layers** for classification  
- 🔹 **Character-level Input Processing** for fine-grained pattern analysis  

---

### 🔍 Model Insights  
✔ **Character-based analysis** improves detection of **obfuscated payloads** (e.g., encoding or insertion tricks).  
✔ **Graph-based input** learns relationships between characters → better recognition of subtle attack variations.  
✔ Strong results for **SQLi**, but performance dips on **XSS/Command Injection** due to class imbalance.  

---

### ✅ Pros vs ❌ Cons  

**✅ Strengths**  
- Robust feature extraction with GCN  
- Fine-grained character-level analysis  
- Regularization improves generalization  
- Scalable to other security tasks  

**❌ Limitations**  
- Computationally heavy compared to rule-based approaches  
- Sensitive to dataset imbalance  
- Limited interpretability  

---

## 📂 Dataset & Preprocessing  
- 📊 **Original Dataset**: [SQLi & XSS Dataset](https://www.kaggle.com/datasets/alextrinity/sqli-xss-dataset)  
- ➕ **Added Benign Samples**:  
  - Common usernames & passwords (RockYou)  
  - Non-malicious queries & admin text  
  - General short text samples  

**Preprocessing:**  
- Converted raw payloads → **graph structure**  
- Tokenization tuned for **fine-grained representation**  
- Scripts & modified datasets are included in this repo  

---

## 🔗 Resources & References  
- 📌 Dataset: [SQLi & XSS Dataset](https://www.kaggle.com/datasets/alextrinity/sqli-xss-dataset)  
- 📌 Preprocessing & Code (inspired by earlier forks):  
  - [BharathRam125/InjectionDetector](https://github.com/BharathRam125/InjectionDetector)  
  - [SaiyanSai/InjectionDetector](https://github.com/SaiyanSai/InjectionDetector)  

✨ This repo (**Web-Injection-Detector**) builds upon prior work, with improvements and custom modifications as part of **M.Tech Minor Project**.

---

## 🚀 Future Work  
- ⚖️ Improve **class balance** (more XSS & command injection samples)  
- 📈 Enhance **feature representation** with embeddings  
- 🌍 Expand datasets with **real-world benign & malicious traffic**  
- ⚡ Tune GCN hyperparameters for higher accuracy  
- 🌐 Deploy in real-time **WAF pipelines**  

---

## 📌 Project Status  
✅ Completed as **M.Tech Semester II Minor Project**  
🛡️ Focus: Web Security – Injection Attack Detection  
🚀 Foundation for future research in **Zero Trust & Policy Enforcement**  

---

> 🔐 *“Securing the web by detecting injection attacks before they strike.”*
