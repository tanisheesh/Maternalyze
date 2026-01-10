<div align="center">

# 👶 Maternalyze
### *AI-Powered Pregnancy Health Predictions*

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-maternalyze.onrender.com-blue?style=for-the-badge)](https://maternalyze.onrender.com/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

*Empowering healthcare professionals with intelligent pregnancy risk assessment*

</div>

## 🚀 **Live Application**

**🌟 [Try Maternalyze Now →](https://maternalyze.onrender.com/)**

Experience the full application with real-time ML predictions for pregnancy health assessment.


## 🎯 **Overview**

Maternalyze is an advanced web-based Machine Learning prediction portal designed for pregnancy healthcare. It provides intelligent risk assessment for **Gestational Diabetes Mellitus (GDM)** and **Child Outcome predictions** through sophisticated ML models, delivering actionable insights with beautiful, intuitive visualizations.

<div align="center">

### 🛠️ **Tech Stack**

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/LightGBM-00C853?style=for-the-badge&logo=lightgbm&logoColor=white" alt="LightGBM">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=NumPy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white" alt="Chart.js">
  <img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white" alt="Render">
</p>

</div>


## ✨ **Key Features**

<table>
<tr>
<td width="50%">

### 🎨 **User Experience**
- 📋 **Intuitive Forms** - Structured input with clear labels and units
- 🎯 **Smart Validation** - Real-time input validation and guidance  
- 📱 **Responsive Design** - Works seamlessly on all devices
- 🎨 **Beautiful UI** - Modern, clean interface with smooth animations

</td>
<td width="50%">

### 🧠 **AI & Analytics**
- 🤖 **ML Predictions** - Advanced LightGBM models for accurate risk assessment
- 📊 **Interactive Charts** - Dynamic visualizations with Chart.js
- 📈 **Feature Importance** - Understand which factors drive predictions
- ⚡ **Real-time Results** - Instant predictions with detailed precautions

</td>
</tr>
</table>


## 🏥 **Prediction Models**

### 🩺 **Gestational Diabetes Mellitus (GDM)**
Assess the risk of developing gestational diabetes during pregnancy based on:
- Patient demographics and medical history
- BMI and physical measurements  
- Blood glucose levels
- Ethnicity and risk factors

### 👶 **Child Outcome Prediction**
Evaluate potential complications and outcomes for newborns considering:
- Maternal health indicators
- Delivery circumstances
- Fetal development metrics
- APGAR scores and birth weight

## 🎮 **How to Use**

1. **🏠 Navigate** - Start at the main portal to choose your prediction type
2. **📝 Input Data** - Fill in the comprehensive medical forms with patient information
3. **🔮 Get Predictions** - Receive instant ML-powered risk assessments
4. **📊 Analyze Results** - Review detailed charts, probabilities, and clinical recommendations
5. **📋 Take Action** - Follow personalized precautionary measures and guidelines


## 🏗️ **Architecture**

```
📁 Maternalyze/
├── 🖥️  backend/           # FastAPI server & ML models
│   ├── app.py            # Main application & API endpoints
│   ├── model_utils.py    # Data preprocessing & utilities
│   └── requirements.txt  # Python dependencies
├── 🎨 frontend/          # Web interface
│   ├── index.html        # Landing page & navigation
│   ├── gdm_prediction.html    # GDM prediction interface
│   ├── child_prediction.html  # Child outcome interface
│   ├── style.css         # Modern styling & animations
│   ├── script.js         # Interactive functionality
│   └── config.js         # Environment configuration
├── 🤖 models/            # Pre-trained ML models
└── 📊 data/              # Training datasets
```



## 🚀 **Deployment**

The application is deployed on **Render** with automatic scaling and continuous deployment from the main branch.

**Production URL:** [https://maternalyze.onrender.com/](https://maternalyze.onrender.com/)

### 🔧 **Local Development**

```bash
# Install dependencies
pip install -r requirements.txt

# Start the server
cd backend && uvicorn app:app --host 127.0.0.1 --port 8000 --reload

# Access the application
open http://127.0.0.1:8000
```


## 📊 **API Documentation**

Interactive API documentation is available at:
- **Swagger UI:** [/docs](https://maternalyze.onrender.com/docs)
- **ReDoc:** [/redoc](https://maternalyze.onrender.com/redoc)

### 🔗 **Main Endpoints**
- `POST /predict_gdm` - Gestational Diabetes prediction
- `POST /predict_child` - Child outcome prediction
- `GET /` - Web application interface


### 📄 **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

</div>
