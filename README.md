<<<<<<< HEAD
# fraud_detection
=======
# 🕵️‍♂️ Fraud Detection

This project implements a machine learning system to detect fraudulent financial transactions using logistic regression and exploratory data analysis (EDA).

## 🚀 Features

- Exploratory data analysis (EDA).
- Data preprocessing and encoding.
- Machine learning models for classification.
- Streamlit app for interactive fraud detection.

## 🛠️ Installation

1. Clone the repository:

```bash
git clone https://github.com/onedmilson/fraud_detection.git
cd fraud_detection
```

2. Create and activate a virtual environment:

```bash
python -m venv venv
venv\Scripts\activate  # On Windows
```

3. Install dependencies:
```bash
python -m venv venv
pip install -r requirements.txt
```

## 📁 Project Structure
```bash
fraud_detection/
│
├── app/                   # Streamlit application
│   └── fraud_detection.py
├── data/                  # Raw and processed datasets
│   └── AIML Dataset.csv
├── models/                # Saved model files
│   └── fraud_detection_pipeline.pkl
├── notebooks/             # Jupyter Notebooks for EDA and modeling
│   └── analysis_model.ipynb
├── requirements.txt       # Project dependencies
└── README.md
```

## 🧠 Dataset
This project uses the [Fraud Detection Dataset](https://www.kaggle.com/datasets/amanalisiddiqui/fraud-detection-dataset?resource=download) from Kaggle.

## 🎯 Usage
Run the app locally:
```bash
streamlit run app/fraud_app.py
```

## 📄 License
MIT License
>>>>>>> 8a3e7cd (Initial commit)
