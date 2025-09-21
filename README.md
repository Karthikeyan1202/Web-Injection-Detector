# Web Injection Detector – GCN-based Model  
*M.Tech (Cyber Security) – Semester II Minor Project*  
🔗 Repository: [Web-Injection-Detector](https://github.com/Karthikeyan1202/Web-Injection-Detector)  

---

## Contributors
<p align="left">
  <a href="https://github.com/Karthikeyan1202" title="Karthikeyan1202">
    <img src="https://avatars.githubusercontent.com/Karthikeyan1202" width="80" style="border-radius:50%;" alt="Karthikeyan1202"/>
  </a>
  <a href="https://github.com/BharathRam125" title="BharathRam125">
    <img src="https://avatars.githubusercontent.com/BharathRam125" width="80" style="border-radius:50%;" alt="BharathRam125"/>
  </a>
  <a href="https://github.com/SaiyanSai" title="SaiyanSai">
    <img src="https://avatars.githubusercontent.com/SaiyanSai" width="80" style="border-radius:50%;" alt="SaiyanSai"/>
  </a>
</p>

<p align="left">
  <a href="https://github.com/Karthikeyan1202"><b>@Karthikeyan1202</b></a> • 
  <a href="https://github.com/BharathRam125"><b>@BharathRam125</b></a> • 
  <a href="https://github.com/SaiyanSai"><b>@SaiyanSai</b></a>
</p>

---

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=22&duration=4000&pause=1000&color=36BCF7&center=true&vCenter=true&width=750&lines=Web+Injection+Attack+Detection+using+GCN;Detecting+SQLi%2C+XSS+and+Command+Injection;Graph-Based+Payload+Modeling+for+Security;Advancing+M.Tech+Cybersecurity+Research">
</p>

---

## Overview
A **Graph Convolutional Network (GCN)-based system** for detecting **Web Injection Attacks** at the Web Application Firewall (WAF) level.  
Payloads are structured into **graph-based representations** to enhance anomaly detection and resist obfuscation.

**Focus Areas**
- SQL Injection (SQLi)  
- Cross-Site Scripting (XSS)  
- Command Injection  

---

## Model Architecture
- 3-Layer Graph Convolutional Network  
- Batch Normalization & Dropout  
- Fully Connected Classification Layers  
- Character-level tokenization for fine-grained detection  

---

## Key Insights
**Strengths**
- Graph-based feature extraction  
- Resilient to obfuscation and bypass techniques  
- Strong results on SQL Injection  

**Limitations**
- Dataset imbalance affects XSS & Command Injection accuracy  
- Computationally expensive  
- Limited interpretability compared to rule-based methods  

---

## Dataset & Preprocessing
- **Base Dataset**: [SQLi & XSS Dataset](https://www.kaggle.com/datasets/alextrinity/sqli-xss-dataset)  
- **Augmentation**: Benign payloads (RockYou dataset, admin queries, random strings)  
- **Pipeline**:  
  - Payloads → Graph conversion  
  - Character-level tokenization  
  - Feature encoding optimized for GCN  

---

## References
- Dataset: [SQLi & XSS Dataset](https://www.kaggle.com/datasets/alextrinity/sqli-xss-dataset)  
- Baselines & Forks:  
  - [BharathRam125/InjectionDetector](https://github.com/BharathRam125/InjectionDetector)  
  - [SaiyanSai/InjectionDetector](https://github.com/SaiyanSai/InjectionDetector)  

---

## Future Work
- Balance dataset for XSS & Command Injection  
- Enhance tokenization with embeddings  
- Collect real-world traffic samples  
- Tune GCN hyperparameters  
- Integrate with WAF pipelines for real-time deployment  

---

## Project Status
- Completed as **M.Tech Semester II Minor Project**  
- Domain: **Web Security – Injection Detection**  
- Extensible towards **Zero Trust & Policy Enforcement**  

---

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&duration=3500&pause=1200&color=FF6B6B&center=true&vCenter=true&width=750&lines=Securing+the+Web+from+Injection+Attacks;Powered+by+Graph+Neural+Networks;Towards+Zero+Trust+Architecture">
</p>
