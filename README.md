# 🚀 IntrusionX: SSA-Optimized Conv–LSTM for Network Intrusion Detection  

## 📌 Overview  
**IntrusionX** is a hybrid deep learning framework for **Network Intrusion Detection (IDS)**.  
It combines **Convolutional Neural Networks (CNNs)** for feature extraction with **Long Short-Term Memory (LSTM)** networks for temporal learning.  
To optimize hyperparameters, we use the **Squirrel Search Algorithm (SSA)** — a lightweight swarm intelligence method.  

Our pipeline includes **leak-free preprocessing, stratified data splitting, and dynamic class weighting**, ensuring improved performance on rare attack classes.  

---

## ✨ Key Results  
- **Binary classification (Normal vs Attack):** 98% accuracy, AUC = 0.9986  
- **5-class classification (DoS, Probe, R2L, U2R, Normal):** 87% accuracy, Weighted F1 = 0.90  
- **Rare-class recall:** R2L = 93%, U2R = 71%  

---

## ⚡ Quick Start  

1. **Clone the repo:**  
```bash
git clone https://github.com/TheAhsanFarabi/IntrusionX.git
cd IntrusionX
