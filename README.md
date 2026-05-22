# 🎯 Customer Churn Prediction - ML Career Transformation Project

Transform from **Data Analyst → Data Scientist** with this comprehensive machine learning project!

## 📚 What You'll Master

✅ Exploratory Data Analysis with Business Insights  
✅ Advanced Feature Engineering & Selection  
✅ Handling Imbalanced Datasets  
✅ Multiple ML Algorithms (Logistic Regression, Random Forest, XGBoost)  
✅ Hyperparameter Tuning & Cross-Validation  
✅ Model Evaluation & Interpretability  
✅ Production-Ready Code Structure  
✅ Business Impact Analysis  

## 🚀 Quick Start

```bash
# Clone and setup
git clone https://github.com/Deepthish07/ML-Customer-Churn-Prediction.git
cd ML-Customer-Churn-Prediction

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Download dataset from Kaggle
kaggle datasets download -d blastchar/telco-customer-churn
unzip telco-customer-churn.zip -d data/raw/

# Start Jupyter
jupyter notebook

# Or run everything at once
python run_all.py
```

## 📊 Project Structure

```
ML-Customer-Churn-Prediction/
├── README.md
├── requirements.txt
├── config.yaml
├── run_all.py
├── data/
│   ├── raw/                   # Download dataset here
│   └── processed/             # Processed data
├── notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_Feature_Engineering.ipynb
│   ├── 03_Model_Building.ipynb
│   └── 04_Model_Evaluation.ipynb
├── src/
│   ├── __init__.py
│   ├── data_loader.py
│   ├── feature_engineering.py
│   ├── model_builder.py
│   ├── model_evaluation.py
│   └── visualizations.py
├── models/
│   └── trained_models/
└── results/
```

## 🎓 Learning Path: Analyst → Data Scientist

**Phase 1:** Data Exploration → **Phase 2:** Feature Engineering & Modeling → **Phase 3:** Evaluation & Insights

## 📊 Dataset

- **Source:** Kaggle Telecom Customer Churn
- **Records:** 7,043 customers
- **Features:** 21 (demographics, services, charges)
- **Target:** Churn prediction

## 🤖 Models

1. Logistic Regression (Baseline)
2. Random Forest (Ensemble)
3. XGBoost (Best Performance)

## 🔍 How to Run

```bash
# Option 1: Run everything at once
python run_all.py

# Option 2: Run step-by-step with Jupyter
jupyter notebook
# Run notebooks: 01 → 02 → 03 → 04
```

## 📈 Expected Metrics

| Model | Accuracy | Precision | Recall | F1 | AUC-ROC |
|-------|----------|-----------|--------|----|----|
| Logistic Regression | 80.1% | 65.2% | 52.3% | 0.581 | 0.843 |
| Random Forest | 81.5% | 68.4% | 56.7% | 0.619 | 0.868 |
| **XGBoost** | **82.1%** | **70.1%** | **58.9%** | **0.640** | **0.881** |

## 💡 Business Impact

- Identify high-churn-risk customers
- Target retention efforts effectively
- Reduce customer acquisition costs
- Improve lifetime value

## 🎓 Interview Ready

This project covers:
- Full ML lifecycle
- Statistical fundamentals
- Model evaluation & selection
- Business problem-solving
- Code best practices

---

**Start your transformation: Begin with `notebooks/01_EDA.ipynb`! 🚀**
