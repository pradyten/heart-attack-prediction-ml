# Heart Attack Prediction using Machine Learning

Predicting cardiovascular disease risk using ensemble ML methods with comprehensive EDA and feature importance analysis

## 📋 Table of Contents
- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Author](#author)

## 🎯 Overview

Predicting cardiovascular disease risk using ensemble ML methods with comprehensive EDA and feature importance analysis.

This project demonstrates:
- End-to-end machine learning pipeline
- Data preprocessing and feature engineering
- Model training and evaluation
- Results visualization and interpretation

## 🔍 Problem Statement

Heart attacks are a leading cause of death globally (17.9M deaths/year per WHO). Early risk prediction using patient health metrics can enable preventive interventions and save lives.

## 📊 Dataset

**Source:** Cardiovascular disease dataset with patient health indicators including age, cholesterol, blood pressure, and lifestyle factors

**Note:** The dataset is not included in this repository due to size constraints. Please download it separately from the source mentioned in the notebook or contact the author for access instructions.

## 🔬 Methodology

This project employs the following techniques and models:

- **XGBoost**
- **Random Forest**
- **Logistic Regression**
- **Ensemble Methods**
- **Feature Engineering**
- **Model Interpretability**

The notebook includes:
- Exploratory Data Analysis (EDA)
- Data preprocessing and cleaning
- Feature engineering and selection
- Model training and hyperparameter tuning
- Performance evaluation and visualization
- Results interpretation

## 📈 Results

High-accuracy risk prediction with feature importance insights for clinical decision support

Detailed results, metrics, and visualizations are available in the Jupyter notebook.

## 🚀 Installation

### Prerequisites
- Python 3.8 or higher
- pip package manager
- Jupyter Notebook or JupyterLab

### Setup

1. Clone the repository:
```bash
git clone https://github.com/pradyten/heart-attack-prediction-ml.git
cd heart-attack-prediction-ml
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

4. Download necessary data files (see Dataset section)

## 💻 Usage

1. Launch Jupyter Notebook:
```bash
jupyter notebook
```

2. Open `heart-attack-prediction.ipynb` in the Jupyter interface

3. Run the cells sequentially from top to bottom

4. Modify parameters and experiment with different approaches as needed

**Note:** Some cells may require significant computational resources and time to execute, especially model training sections.

## 📁 Project Structure

```
heart-attack-prediction-ml/
│
├── heart-attack-prediction.ipynb          # Main analysis notebook
├── requirements.txt              # Python dependencies
├── README.md                     # This file
└── .gitignore                    # Git ignore rules
```

## 🛠 Technologies Used

- **Python** - Primary programming language
- **Jupyter Notebook** - Interactive development environment
- **NumPy & Pandas** - Data manipulation and analysis
- **Matplotlib & Seaborn** - Data visualization
- **Scikit-learn** - Machine learning algorithms and utilities
- **TensorFlow/Keras** - Deep learning framework (if applicable)
- Additional libraries as listed in `requirements.txt`

## 👨‍💻 Author

**Pradyumn Tendulkar**

Data Science Graduate Student | ML Engineer

- GitHub: [@pradyten](https://github.com/pradyten)
- LinkedIn: [Pradyumn Tendulkar](https://www.linkedin.com/in/pradyumn-tendulkar)
- Email: pktendulkar@wpi.edu

---

⭐ If you found this project helpful, please consider giving it a star!

📝 **Note:** This project was developed as part of my Data Science portfolio. Feel free to fork, modify, and use for learning purposes. For any questions or collaboration opportunities, please reach out!
