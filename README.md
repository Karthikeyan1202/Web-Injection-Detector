# Web Injection Detector – GCN-based Model  
*M.Tech (Cyber Security) – Semester (II) Minor Project*  
Repository: [Web-Injection-Detector](https://github.com/Karthikeyan1202/Web-Injection-Detector)  

---

## Contributors
- [@Karthikeyan1202](https://github.com/Karthikeyan1202)  
- [@BharathRam125](https://github.com/BharathRam125)  
- [@SaiyanSai](https://github.com/SaiyanSai)  

---

## Overview
This project implements a **Graph Convolutional Network (GCN)-based approach** for detecting **Web Injection Attacks** at the Web Application Firewall (WAF) level.  

By converting web payloads into **graph-based representations**, the system enables enhanced **pattern recognition** and improved detection of **obfuscated or adversarial attack payloads**.  

**Target Attacks**
- SQL Injection (SQLi)  
- Cross-Site Scripting (XSS)  
- Command Injection  

---

## Model Architecture
- Multi-layer Graph Convolutional Network (GCN)  
- Batch Normalization and Dropout regularization  
- Fully connected classification layers  
- Character-level tokenization for input representation  

---

## Key Insights
**Strengths**
- Learns relational patterns between payload characters  
- Effective against obfuscation and bypass techniques  
- Strong detection performance on SQL Injection  

**Limitations**
- Performance imbalance on XSS and Command Injection due to dataset skew  
- Computationally more expensive than rule-based detection  
- Interpretability challenges compared to signature-based WAF rules  

---

## Dataset & Preprocessing
- **Base Dataset**: [SQLi & XSS Dataset](https://www.kaggle.com/datasets/alextrinity/sqli-xss-dataset)  
- **Augmentations**: Added benign samples (RockYou dataset, randomized queries, admin test data)  
- **Pipeline**:  
  1. Raw payloads converted to graph structures  
  2. Character-level tokenization  
  3. Encoded feature vectors optimized for GCN processing  

---

## References
- [SQLi & XSS Dataset](https://www.kaggle.com/datasets/alextrinity/sqli-xss-dataset)  
- [BharathRam125/InjectionDetector](https://github.com/BharathRam125/InjectionDetector)  
- [SaiyanSai/InjectionDetector](https://github.com/SaiyanSai/InjectionDetector)  

---

## Future Work
- Address dataset imbalance for XSS and Command Injection  
- Incorporate embeddings for tokenization  
- Collect and integrate real-world benign and malicious traffic  
- Optimize hyperparameters for improved accuracy  
- Explore deployment in real-time WAF pipelines  

---

## Project Status
- Completed as **M.Tech Semester II Minor Project**  
- Domain: Web Security – Injection Attack Detection  

