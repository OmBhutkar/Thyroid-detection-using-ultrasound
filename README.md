# 🧬 AI Thyroid Nodule Classifier

A deep learning application for thyroid ultrasound image analysis using CNN. Classifies thyroid nodules as benign or malignant with professional PDF reporting.

![Python](https://img.shields.io/badge/python-v3.8+-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-1.x-red.svg)

## ✨ Features

- 🤖 **AI Classification**: CNN-based thyroid nodule analysis
- 📊 **Confidence Scoring**: Detailed probability analysis  
- 📄 **PDF Reports**: Professional medical reports with patient info
- ⚡ **Real-time**: Instant results in under 2 seconds
- 🎨 **Modern UI**: Interactive web interface

## 🚀 Quick Start

1. **Install dependencies**
```bash
pip install -r requirements.txt
```

2. **Add model files**
- Place `cnn_thyroid_model.h5` and `label_encoder.pkl` in project directory

3. **Run application**
```bash
streamlit run streamlit_app.py
```

4. **Open browser** → `http://localhost:8501`

## 📋 Usage

1. Upload thyroid ultrasound image (JPG/PNG)
2. View AI classification results
3. Fill patient information
4. Generate & download PDF report

## 🔧 Requirements

- Python 3.8+
- 4GB RAM minimum
- Model files: `cnn_thyroid_model.h5`, `label_encoder.pkl`

## ⚠️ Important Notice

**FOR RESEARCH PURPOSES ONLY** - This tool is designed for educational and research use. Always consult qualified healthcare professionals for medical decisions.

## 📄 License

MIT License - See LICENSE file for details.
