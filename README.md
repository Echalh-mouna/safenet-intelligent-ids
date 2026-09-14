# 🛡️ SafeNet Intelligent IDS

> Intelligent Intrusion Detection System based on Machine Learning and Deep Learning

SafeNet IDS is an intelligent Intrusion Detection System (IDS) designed to analyze network traffic and detect malicious or abnormal activities using Machine Learning and Deep Learning techniques.

The system combines network traffic preprocessing, feature extraction, multiple classification models and an interactive web application for PCAP/PCAPNG traffic analysis.

---

## 📌 Project Overview

With the increasing complexity of cyberattacks, traditional intrusion detection approaches based mainly on predefined signatures may struggle to detect new or evolving threats.

SafeNet IDS aims to provide a more intelligent and adaptive approach by learning patterns from network traffic and automatically classifying normal and malicious activities.

The project focuses on:

- Network traffic analysis
- Data preprocessing and feature engineering
- Machine Learning classification
- Deep Learning classification
- Model optimization
- Intrusion detection
- PCAP/PCAPNG analysis
- Performance evaluation
- Interactive visualization

---

## 🎯 Objectives

The main objectives of the project are to:

- Analyze and preprocess network traffic datasets.
- Extract relevant features from network traffic.
- Train Machine Learning and Deep Learning models.
- Detect normal and malicious network activities.
- Reduce false positives.
- Compare different classification approaches.
- Optimize the most promising models.
- Provide an interactive interface for PCAP analysis.
- Build an extensible architecture for future real-time intrusion detection.

---

## 🧠 Machine Learning & Deep Learning Models

Several models were developed and compared during the project.

| Model | Type | Main Purpose |
|-------|------|--------------|
| Random Forest | Machine Learning | Robust and interpretable classification |
| XGBoost | Machine Learning | Fast and accurate classification |
| SVM | Machine Learning | Non-linear class separation |
| DNN | Deep Learning | Learning complex feature representations |
| CNN | Deep Learning | Automatic pattern extraction |
| LSTM | Deep Learning | Sequential and temporal analysis |
| Ensemble | Hybrid | Combination of multiple model predictions |

---

## 📊 Datasets

The project uses several network intrusion detection datasets:

### CICIDS2017

A network traffic dataset containing normal traffic and multiple attack scenarios.

### NSL-KDD

A widely used dataset for intrusion detection research containing different categories of network attacks.

### UNSW-NB15

A network intrusion dataset containing normal and malicious traffic.

> Dataset files are not included in this repository because of their size and/or licensing considerations.

---

## 🔄 Data Processing Pipeline

The data processing pipeline includes:

```text
Raw Network Data
       │
       ▼
Data Cleaning
       │
       ▼
Duplicate & Missing Value Handling
       │
       ▼
Feature Transformation
       │
       ▼
Categorical Encoding
       │
       ▼
Feature Scaling / Normalization
       │
       ▼
Class Balancing
       │
       ▼
Train / Validation / Test Split
       │
       ▼
Model Training
       │
       ▼
Model Evaluation
