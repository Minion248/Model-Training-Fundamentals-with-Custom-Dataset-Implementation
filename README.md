# **Model Training Fundamentals - Titanic Survival Prediction**

## **📌 Overview**
This project implements key machine learning concepts from **Chapter 4 of "Hands-On Machine Learning with Scikit-Learn, TensorFlow, and Keras"** using the Titanic survival dataset. It covers:
- **Linear models** (OLS, Ridge, Lasso, Elastic Net)
- **Optimization methods** (Batch GD, SGD, Mini-batch SGD)
- **Logistic Regression** for classification
- **Model evaluation** with learning curves and hyperparameter tuning

## **📂 Project Structure**
```
├── data/                    # Processed dataset (train.csv)
├── notebooks/
│   ├── EDA.ipynb            # Exploratory Data Analysis
│   ├── Model_Training.ipynb # Full training pipeline
│   └── Results_Analysis.ipynb
├── models/                  # Saved model weights
├── README.md                # This file
└── requirements.txt         # Python dependencies
```

## **🚀 Key Features**
✔ **Data Preprocessing Pipeline**  
- Missing value imputation (median/mode)
- Categorical encoding (LabelEncoder)  
- Polynomial feature engineering (degree=2)  
- Standardization (StandardScaler)  

✔ **Model Implementations**  
| Model                | Accuracy | Training Time | Best Params       |
|----------------------|----------|---------------|-------------------|
| Logistic Regression  | 82.1%    | 0.015s        | Default           |
| SGD Classifier       | 79.3%    | 0.008s        | alpha=0.0001      |
| Ridge Classifier     | 81.0%    | 0.003s        | Default           |

✔ **Visualizations**  
- Learning curves  
- Feature correlation heatmaps  
- Survival rate by demographics  

## **🛠️ Installation**
1. Clone repo:
   ```bash
   git clone https://github.com/yourusername/titanic-ml-fundamentals.git
   cd titanic-ml-fundamentals
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

 

 
