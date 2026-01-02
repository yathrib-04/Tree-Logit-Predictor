
## 🚀 Live Demo

- **Logistic Regression App**: [https://logistic-predictor.onrender.com](https://logistic-predictor.onrender.com)  
- **Decision Tree App**: [https://decision-tree-prhd.onrender.com](https://decision-tree-prhd.onrender.com)
-   
# 🌸 Overview

A machine learning web app for Iris flower classification using **Logistic Regression** and **Decision Tree** algorithms, with FastAPI backends and modern, responsive frontends.

## ✨ Features

- Logistic Regression & Decision Tree classifiers  
- FastAPI backend with Pydantic validation  
- Modern, responsive neon-themed UI  
- Real-time predictions via web interface  

## 🛠 Tech Stack

**Backend:** FastAPI, Scikit-learn, Joblib, NumPy, Pydantic  
**Frontend:** HTML5, Bootstrap 5.3.2, Vanilla JS, Custom CSS  
**ML Models:** Logistic Regression (with StandardScaler), Decision Tree (max_depth=3)  

## Setup & Run

### 1. Create a virtual environment
```bash
python -m venv venv
# Logistic Regression App
cd logistic_app
pip install -r requirements.txt
cd ..

# Decision Tree App
cd decision_tree_app
pip install -r requirements.txt
cd ..
# Logistic Regression (Port 9050)
uvicorn main:app --host 127.0.0.1 --port 9050

# Decision Tree (Port 9051)
uvicorn main:app --host 127.0.0.1 --port 9051
