# 🛡️ Web Injection Detector – GCN-based Model  
📌 *M.Tech (Cyber Security) – Semester II Minor Project*  
🔗 Repository: [Web-Injection-Detector](https://github.com/Karthikeyan1202/Web-Injection-Detector)  

---

## 👨‍💻 Project Team  
| Member | GitHub Profile |
|--------|----------------|
| 🧑‍🚀 Karthikeyan | [@Karthikeyan1202](https://github.com/Karthikeyan1202) |
| ⚔️ Bharath | [@BharathRam125](https://github.com/BharathRam125) |
| 🐉 Saiyan | [@SaiyanSai](https://github.com/SaiyanSai) |

---

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=24&duration=4000&pause=1000&color=00F7FF&center=true&vCenter=true&width=700&lines=Initializing+Security+Protocols...;Deploying+GCN-based+Detector...;Scanning+for+SQLi+XSS+Command+Injection...;Web+Applications+Secured!+%E2%9C%85" alt="Typing Animation">
</p>

---

## 📌 Overview  
A **Graph Convolutional Network (GCN)-based system** for detecting **Web Injection Attacks** at the **Web Application Firewall (WAF)** level.  
By structuring web request payloads into **graph-based representations**, the model enhances **pattern recognition and anomaly detection**.  

⚠️ **Disclaimer**  
- 🚧 Work-in-progress (research stage)  
- 🗂️ Dataset used is experimental (test coverage only)  
- 🛑 Focused on **SQL Injection, XSS, Command Injection**  
- ⚖️ Dataset imbalance requires improvement for XSS/Command Injection  

---

## 🏗️ Model Architecture  
✨ Powered by **Graph Convolutional Networks (GCN)**:  
- 🔹 3-Layer GCN for feature extraction  
- 🔹 Batch Normalization & Dropout for stability  
- 🔹 Fully Connected Layers for classification  
- 🔹 Character-level input processing for fine-grained detection  

---

### 🔍 Model Insights  
✔ Detects **obfuscated payloads** (encoding, bypass tricks)  
✔ Graph structure learns **relationships between characters**  
✔ High performance on **SQL Injection**  
❌ Needs better balance for **XSS & Command Injection**  

---

### ✅ Pros vs ❌ Cons  

**✅ Strengths**  
- 🧠 Robust graph-based feature extraction  
- 🔍 Fine-grained character-level analysis  
- ⚡ Regularization improves generalization  
- 🔒 Scalable to other security tasks  

**❌ Limitations**  
- 🖥️ Computationally heavy  
- ⚖️ Sensitive to dataset imbalance  
- 🕵️ Limited interpretability vs. rule-based methods  

---

## 📂 Dataset & Preprocessing  
- 📊 **Original Dataset**: [SQLi & XSS Dataset](https://www.kaggle.com/datasets/alextrinity/sqli-xss-dataset)  
- ➕ **Benign Samples Added**:  
  - RockYou usernames & passwords  
  - Admin/normal queries  
  - Randomized short phrases  

🔧 **Preprocessing Pipeline**  
- Raw payloads ➝ **graph conversion**  
- Character-level tokenization  
- Feature representation optimized for GCN  

---

## 🔗 References & Inspiration  
- 📌 Dataset: [SQLi & XSS Dataset](https://www.kaggle.com/datasets/alextrinity/sqli-xss-dataset)  
- 📌 Forks & Baselines:  
  - [BharathRam125/InjectionDetector](https://github.com/BharathRam125/InjectionDetector)  
  - [SaiyanSai/InjectionDetector](https://github.com/SaiyanSai/InjectionDetector)  

✨ This repo (**Web-Injection-Detector**) builds upon prior forks with **custom modifications & improvements** as part of **M.Tech Minor Project**.

---

## 🚀 Future Work  
- ⚖️ Balance datasets (XSS & Command Injection)  
- 📈 Enhance tokenization with embeddings  
- 🌍 Collect real-world benign + malicious samples  
- ⚡ Tune GCN hyperparameters  
- 🌐 Deploy detector inside **WAF pipelines**  

---

## 📌 Project Status  
✅ Completed as **M.Tech Semester II Minor Project**  
🛡️ Domain: Web Security – Injection Attack Detection  
🚀 Extensible towards **Zero Trust & Policy Enforcement Research**  

---

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&size=22&duration=4000&pause=1000&color=FF5733&center=true&vCenter=true&width=700&lines=Securing+the+Web+from+Injection+Attacks...;Powered+by+Graph+Neural+Networks+%F0%9F%94%8D;Advancing+Cybersecurity+Research...;Towards+Zero+Trust+Architecture..." alt="Typing Animation">
</p>

