# 🎬 OTT Churn Prediction System

A production-ready machine learning solution that predicts customer churn for Over-The-Top (OTT) streaming platforms using XGBoost with real-time health monitoring and full-stack deployment.

**Status:** ✅ Production Ready  
**Tech:** Python · FastAPI · React  

---

## 🎯 Overview

The OTT Churn Prediction System predicts which streaming service customers are likely to cancel their subscriptions. It leverages machine learning to identify at-risk customers, enabling proactive retention strategies.

### Key Capabilities
- Batch Predictions (CSV / XLSX upload)
- Real-time backend health monitoring
- Schema validation with detailed error feedback
- Automated full-stack startup
- Production-ready deployment setup

---

## ✨ Key Features

### 🤖 Machine Learning
- XGBoost primary model with Random Forest & Logistic Regression fallback
- Advanced feature engineering (5 engineered features)
- Intelligent NaN handling with domain-aware strategies
- Data drift detection for model performance monitoring

### 🌐 Frontend
- Interactive dashboard for batch predictions
- Live backend health indicator (Green / Red)
- Responsive UI using Tailwind CSS
- User-friendly validation & error handling

### ⚙️ Backend
- FastAPI async framework
- CSV and XLSX support via pandas
- Strict 13-column schema validation
- Descriptive HTTP error handling

### 🚀 DevOps
- One-command startup for backend + frontend
- Automatic port cleanup
- Parallel service execution
- Health verification before completion

---

## 💻 Tech Stack

### Backend
- FastAPI 0.115.0  
- Uvicorn 0.30.0  
- XGBoost  
- Scikit-learn 1.6.1  
- Pandas 2.2.3  
- Pydantic 2.10.0  

### Frontend
- React 18  
- Vite  
- Tailwind CSS  
- JavaScript (JSX)  

### Infrastructure
- Python 3.9+  
- Node.js 18+  
- macOS / Linux / Windows  

---

## 🚀 Quick Start

### Prerequisites
- Python 3.9+
- Node.js 18+
- npm or yarn

### Installation

```bash
git clone https://github.com/kananjethwani24/ott-churn-prediction-system.git
cd ott-churn-prediction-system
