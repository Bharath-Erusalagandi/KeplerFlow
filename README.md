# 🔭 KeplerFlow: AI-Powered Exoplanet Discovery 🪐

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![NASA Space Apps](https://img.shields.io/badge/NASA%20Space%20Apps-2025-blue)](https://www.spaceappschallenge.org/)

An AI-p**KeplerFlow** is a research-grade machine learning system designed to discover and classify exoplanets using data from NASA's Kepler, K2, and TESS missions. By implementing advanced ensemble methodologies, it achieves high precision in distinguishing between confirmed exoplanets and false positives.
 with high accuracy.

## 🚀 Features

- **Advanced Ensemble Model**: Combines Random Forest, XGBoost, LightGBM, Gradient Boosting, and ExtraTrees classifiers.
- **Superior Performance**: Achieves ~82% accuracy with high ROC-AUC scores through research-grade feature engineering.
- **NASA Data Integration**: Trained on 21,000+ samples across multiple NASA missions.
- **Interactive Web Interface**: Built with Dash for real-time classification and interactive data exploration.
- **Physics-Informed Features**: Incorporates 35+ engineered features including SNR estimates, habitable zone indicators, and planetary density proxies.

## 🛠️ Tech Stack

- **Machine Learning**: `scikit-learn`, `XGBoost`, `LightGBM`, `imbalanced-learn`
- **Frontend**: `Dash`, `Plotly`, `Bootstrap`
- **Data Processing**: `Pandas`, `NumPy`, `Joblib`

## 📋 Prerequisites

- Python 3.8 or higher
- `pip` package manager

## ⚙️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Bharath-Erusalagandi/Nasa-Space-Apps.git
   cd Nasa-Space-Apps
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## 🏃 Usage

### 🌐 Launch the Web Application
To start the interactive detection interface:
```bash
python scripts/launch_keplerflow.py
```
Visit `http://localhost:8050` in your browser to access the application.

### 🧪 Train the Enhanced Model
If you need to retrain the models with fresh data:
```bash
python scripts/keplerflow_pipeline.py
```

## 📊 Dataset Information

The system utilizes harmonized data from:
- **Kepler Mission**: Primary repository for planetary transits.
- **K2 Mission**: Extended mission data providing diverse stellar targets.
- **TESS Mission**: Latest data from the Transiting Exoplanet Survey Satellite.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---
*Created for the 2025 NASA Space Apps Challenge.*
