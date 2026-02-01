# Real-Time Network Intrusion Detection Using Wireshark and Advanced Ensemble Learning Techniques

A complete end-to-end network intrusion detection solution demonstrating traffic analysis using **Wireshark**, machine learning model training with ensemble techniques, and a **Flask**-based graphical web interface for real-time prediction and visualization.

This repository integrates data extraction, preprocessing, training multiple ML models, serialization of models and encoders, and deployment via a lightweight web application.

---

## 🔍 Project Overview

Network intrusion detection systems (NIDS) monitor network traffic to identify malicious or suspicious behavior that could compromise the integrity, confidentiality, or availability of network resources. This project:

- Extracts traffic features from Wireshark packet captures (`WSdata.csv`)
- Trains advanced ensemble models such as **CatBoost** and **LightGBM**
- Saves trained models and preprocessing encoders
- Hosts a **Flask** web interface for real-time inference

> Wireshark is a powerful open-source packet analyzer used for network troubleshooting, protocol analysis, and security forensics. It allows filtering and inspection of data packets captured over live networks or in pcap files. :contentReference[oaicite:0]{index=0}

---

## 🚀 Features

✔ Dataset preprocessing & feature engineering  
✔ Multi-model training (CatBoost, LightGBM, etc.)  
✔ Model persistence using `pickle`  
✔ Flask-based GUI for interactive prediction  
✔ Protocol encoding and feature scaling  
✔ Real-time traffic classification (normal vs. intrusion)

---

###  Clone the Repository

```sh
git clone https://github.com/harilexm/Network-Intrusion-Detection-Using-Wireshark.git
cd Network-Intrusion-Detection-Using-Wireshark
```
