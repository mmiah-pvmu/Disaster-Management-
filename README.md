# 🌍 Disaster Tweet Classification using Machine Learning

This repository contains the dataset, preprocessing scripts, and ML framework from the paper:  
📘 **“An ML-based Approach to Leveraging Social Media for Disaster Type Classification and Analysis Across World Regions” (Computers, MDPI, 2025)**

---

## 📦 Overview

This project applies **Machine Learning (ML)** to classify disaster-related tweets into multiple categories and subcategories.  
It uses **Logistic Regression** and **Random Forest** models trained on **32,000+ labeled tweets** from real-world disaster events.

---

## 🧾 Dataset Description

**Dataset Name:** Combined Disaster Tweet Dataset  
**Total Tweets:** 32,228  
**Sources:** Combined_Tweet_Dataset_Sorted.xls
**Attributes:**


**Categories:**  
🧍 Human-Induced | 🌪️ Natural | ⚖️ Mixed  

**Subcategories:**  
Accidental, Intentional, Climatological, Geophysical, Hydrological, Meteorological, Others

---

## ⚙️ Preprocessing Pipeline

1. **Text Cleaning** – Remove URLs, numbers, punctuation, and stopwords  
2. **Lemmatization** – Normalize words to base form  
3. **Feature Extraction (TF–IDF)** – Convert tweets to numerical features  
4. **Dataset Integration** – Merge CrisisLexT26 + Hurricane Florence datasets  

---

## 💻 Installation

```bash
# Clone this repository
git clone https://github.com/mmiah-pvmu/Disaster-Management.git

# Create virtual environment
python -m venv env
source env/bin/activate  # or use env\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

```

## 👥 Contributors

- **Mohammad Robel Miah**   
- **Lija Akter**   
- **Dr. Ahmed Abdelmoamen Ahmed**   
- **Dr. Louis Ngamassi** 
- **Dr. Thiagarajan Ramakrishnan**

---
## 🪪 License


© 2025 Mohammad Robel Miah, Lija Akter, Ahmed Abdelmoamen Ahmed, Louis Ngamassi, and Thiagarajan Ramakrishnan.


