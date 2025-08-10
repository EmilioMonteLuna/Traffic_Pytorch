# 🚗 Traffic Volume Prediction with PyTorch LSTM

![Traffic](traffic.png)

A deep learning project that predicts hourly traffic volume using PyTorch LSTM networks. This project analyzes traffic patterns on an interstate highway in Minnesota, USA, incorporating weather data and temporal features to make accurate predictions.

---

## 📝 Project Overview

This project demonstrates how to use deep learning (LSTM networks) for time-series regression tasks. It predicts hourly traffic volume based on historical data, weather, and time features. The workflow includes data preprocessing, model building, training, evaluation, and visualization.

---

## ⚡ Quick Start

1. **Clone the repository**
2. **Create and activate a virtual environment**
3. **Install dependencies**
4. **Run the Jupyter notebook**

---

## 📋 Table of Contents
- [Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Visualizations](#visualizations)
- [Results](#results)
- [Project Structure](#project-structure)
- [Customization](#customization)
- [Contributing](#contributing)
- [References](#references)
- [License](#license)

---

## ✨ Features

- LSTM-based regression for traffic prediction
- Data preprocessing and sequence creation
- Multiple evaluation metrics (MSE, MAE, RMSE, R²)
- Visualizations: actual vs. predicted, residuals
- Well-commented code and markdown explanations

---

## 📊 Dataset

- **Source**: UCI Machine Learning Repository
- **Features**: Traffic volume, weather, time, holidays
- **Files**: `train_scaled.csv`, `test_scaled.csv`

---

## 🚀 Installation

### Prerequisites
- Python 3.7+
- pip

### Setup
```bash
git clone <your-repo-url>
cd Traffic_Pytorch
python -m venv venv
venv\Scripts\activate  # Windows
# or
source venv/bin/activate  # Mac/Linux
pip install -r requirements.txt
```

---

## 💻 Usage

1. Open `notebook.ipynb` in Jupyter Notebook
2. Run all cells to:
   - Load and preprocess data
   - Train the LSTM model
   - Evaluate and visualize results

---

## 🏗️ Model Architecture

- Input: Sequence of 12 hours, 66 features
- LSTM layers
- Fully connected layers
- Output: Predicted traffic volume

---

## 📈 Visualizations

- **Actual vs. Predicted**: Line plot
- **Residuals**: Scatter plot
- **Training Loss**: (if enabled)

---

## 🏆 Results

Example metrics (run notebook for your results):
- **MSE**: Mean Squared Error
- **MAE**: Mean Absolute Error
- **RMSE**: Root Mean Squared Error
- **R²**: Coefficient of Determination

---

## 📁 Project Structure

```
Traffic_Pytorch/
├── notebook.ipynb           # Main Jupyter notebook
├── requirements.txt         # Python dependencies
├── README.md                # Project documentation
├── traffic.png              # Project header image
├── best_traffic_model.pth   # Saved best model
└── Data/
    ├── train_scaled.csv    # Training dataset
    ├── test_scaled.csv     # Testing dataset
    └── traffic_enhanced.csv # Enhanced dataset
```

---

## 🔧 Customization

- Change model parameters in the notebook
- Add new features to CSV files and update input size

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Commit and push your changes
4. Create a Pull Request

---

## 📚 References

- UCI Machine Learning Repository - Metro Interstate Traffic Volume
- PyTorch documentation
- Matplotlib, Seaborn

---

## 📄 License

MIT License

---

⭐ **If this project helped you learn, please give it a star!** ⭐
