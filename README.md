# HRV_seizureDetection
# Real-Time AI-Based Seizure Prediction and Pre-Seizure ECG Analysis Using Wearable Data

## Overview

This repository presents two research projects focused on **AI-driven seizure prediction and characterization using wearable ECG signals**. The studies investigate how cardiovascular dynamics—particularly Heart Rate Variability (HRV)—encode physiological changes preceding epileptic seizures.

Both projects were presented as **scientific poster presentations** at international neuroscience conferences and aim to advance practical, wearable-based seizure monitoring systems.

---

## 📌 Project 1

### Real-Time AI-Based Seizure Prediction from Wearable ECG Data

#### Authors

* **Seyedeh Dorsa Akhavan Maroufi** — Medical Student, Shahid Beheshti University of Medical Sciences
* **Mohammad Amin Farajzadeh** — Medical Student, Shahid Beheshti University of Medical Sciences
* **Mohammad Reza Raoufy*** — Associate Professor, Faculty of Medical Sciences, Tarbiat Modares University

---

### Introduction

Epilepsy affects approximately **50–65 million individuals worldwide** and is characterized by unpredictable seizures that may lead to severe physical injuries and long-term complications. Early detection of physiological alterations prior to seizure onset represents a critical step toward preventive intervention.

While EEG remains the clinical gold standard for epilepsy monitoring, continuous EEG acquisition is often impractical in daily life. Wearable devices capable of recording **electrocardiogram (ECG)** signals provide a scalable alternative. Due to strong neurocardiac interactions, ECG signals contain latent biomarkers reflecting autonomic nervous system dynamics preceding seizures.

This project proposes a **real-time artificial intelligence framework** for predicting seizure onset using wearable ECG data.

---

### Methods

* **Dataset:** SeizeIT2 wearable ECG dataset
* **Subjects:** 125 epilepsy patients
* **Recording duration:** 11,640 hours
* **Seizure events:** 818

#### Data Processing

* ECG signals segmented into **5–10 minute windows**
* Optimal analysis window: ~6.5 minutes
* Segments labeled as:

  * Pre-seizure
  * Normal (interictal)
* Artifact-free segments only

#### Feature Extraction

A total of **97 physiological features** were extracted:

* ECG-derived respiration features
* Time-domain HRV metrics
* Frequency-domain HRV metrics
* Nonlinear cardiac dynamics features

#### Machine Learning Models

* Support Vector Machine (SVM)
* Random Forest
* XGBoost

Inter-subject evaluation was performed to assess **model generalizability across patients**.

---


## 📌 Project 2

### Pre-Seizure ECG Signatures of Different Seizure Types: A Time–Frequency and Nonlinear Machine Learning Approach

---

### Introduction

Physiological alterations occurring prior to seizures differ across seizure types and may reflect distinct autonomic nervous system mechanisms. This study investigates whether **pre-seizure ECG dynamics** can distinguish between seizure categories using advanced signal processing and machine learning approaches.

---

### Methods

* Dataset: **SeizeIT2 wearable ECG database**
* Analysis window: **400 seconds preceding seizure onset**
* Only high-quality ECG segments were included

#### Feature Extraction

From each segment, **105 physiological features** were extracted:

* ECG-derived respiration measures
* Time-domain features
* Frequency-domain features
* Nonlinear HRV metrics

#### Dimensionality Reduction

* Linear Discriminant Analysis (LDA)
* Principal Component Analysis (PCA)

#### Classification Models

* Support Vector Machine (SVM)
* Random Forest
* XGBoost

Correlation analysis and statistical testing were applied to evaluate discriminative physiological markers between seizure types.

---

## 🧠 Key Contributions

* Real-time seizure prediction using wearable ECG
* Large-scale wearable dataset analysis
* HRV-based autonomic biomarker discovery
* Cross-subject model generalization
* Seizure-type differentiation using nonlinear dynamics

---

## 🔑 Keywords

Seizure Prediction, Wearable ECG, Artificial Intelligence, Machine Learning, Heart Rate Variability (HRV), Real-Time Monitoring, Inter-Subject Generalizability, Digital Health

---


## 📬 Contact

**Seyedeh Dorsa Akhavan Maroufi**
Email: [dorsamarof@gmail.com](mailto:dorsamarof@gmail.com)

