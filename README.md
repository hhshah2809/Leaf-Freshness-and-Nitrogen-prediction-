# 🌿 Leaf Freshness & Nitrogen Prediction

[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/)
[![React](https://img.shields.io/badge/React-18.2-blue)](https://reactjs.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.95-green)](https://fastapi.tiangolo.com/)

A **web app** to predict **spinach leaf freshness** and extract features using **ML & computer vision**.  

## 🌟 Features
- ✅ Upload leaf images  
- ✅ Predict freshness (Fresh / Not Fresh)  
- ✅ Show probability and features: **GCV, Area, Aspect Ratio, Roundness**  

## 📂 Project Structure
  ML-project/ # Backend (FastAPI + ML)
  ml-project-frontend/ # Frontend (React + Tailwind)
## ⚡ Setup

### Backend
```bash
cd ML-project
python -m venv .venv
source .venv/Scripts/activate   # Windows
pip install -r requirements.txt
uvicorn api.main:app --reload --port 8000
```
### Frontend
```bash
cd ml-project-frontend
npm install
npm start
```
🎯 Usage

Upload a leaf image

Check freshness, probability, and leaf features
