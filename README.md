<div align="center">
  <img src="https://image2url.com/images/1765350651181-06babfba-cc06-40e3-a682-6ff1e65a95d5.png" height="150"/>

<p align="center">
  <h1>Employee Attrition Prediction</h1>
  <h3>Machine Learning + Flask API + DVC Versioning</h3>
</p>

---

<!-- BADGES -->
<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue" />
  <img src="https://img.shields.io/badge/Flask-API-green" />
  <img src="https://img.shields.io/badge/DVC-Enabled-purple" />
  <img src="https://img.shields.io/badge/ML-Project-orange" />
  <img src="https://img.shields.io/badge/Status-Active-success" />
</p>

---

## 📌 Overview

This project predicts whether an employee will leave the company using machine learning.  
It includes a **Flask API**, **DVC for version control**, and a **pre-trained ML model** for real-time predictions.

The objective is to provide HR teams with a data-driven system to identify employees at risk of attrition.

---

## 📁 Project Structure


---

## Project Structure

```text


├── .dvc/
├── data/
│ ├── raw/
│ └── processed/
│
├── .dvcignore
├── .gitignore
│
├── Employee_Attrition_Prediction.ipynb.dvc
│
├── app.py
├── employee_attrition_model.pkl
├── requirements.txt
├── test_api.py.txt
├── Procfile.txt


```

## 🧠 ML Workflow

1. Data Cleaning  
2. Feature Engineering  
3. Model Training (Random Forest / Logistic Regression)  
4. Evaluation (Accuracy, Precision, ROC AUC)  
5. Export model as `employee_attrition_model.pkl`  
6. Serve model via Flask API  

---

## 🏗 System Architecture

```text

      +-------------+
      |   User      |
      +------+------+  
             |
             v
    +--------+---------+
    |   Flask API      |
    |   (app.py)       |
    +--------+---------+
             |
             v
  +----------+-----------+
  |  ML Model (.pkl)     |
  |  Prediction Engine   |
  +----------+-----------+
             |
             v
    +--------+--------+
    |  JSON Response  |
    +-----------------+
```


