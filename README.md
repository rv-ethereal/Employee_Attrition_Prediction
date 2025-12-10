# Employee Attrition Prediction using Machine Learning, Flask API, and DVC

This project predicts whether an employee will leave the company using a trained machine learning model.  
It includes a Flask-based API for real-time predictions and DVC for dataset and model versioning.

---

## Features
- End-to-end machine learning workflow  
- Flask API for real-time prediction  
- DVC used for dataset and notebook versioning  
- Ready for deployment (Heroku supported)  
- Pre-trained model included (`employee_attrition_model.pkl`)

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
