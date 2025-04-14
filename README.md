
# 🏥 Health Insurance Charge Prediction

Welcome to the **Health Insurance Charge Prediction** project! This repository contains a machine learning solution that uses predictive modeling to estimate individual health insurance charges based on key personal attributes. The goal is to help insurers adopt **fairer, personalized, and data-driven premium pricing strategies**.

---

## 💡 Pain Point: Lack of Personalized Pricing in Health Insurance

Health insurance companies often struggle with offering fair and personalized pricing for customers due to reliance on outdated, one-size-fits-all actuarial models. These traditional methods fail to accurately factor in key risk variables like **age**, **gender**, and **smoking status**, which can lead to:

- **Overcharging low-risk individuals**, pushing them away from coverage.  
- **Undercharging high-risk individuals**, resulting in financial strain for insurers.  
- **Inefficiencies in pricing strategies**, reducing competitiveness in the market.

---

## 🎯 Project Objective

To solve this challenge, I developed a machine learning pipeline that predicts individual insurance charges using regression models. The project enables:
- Smarter risk assessment
- Transparent and fair premium pricing
- Improved customer satisfaction and business profitability

---

## 🧠 ML Models Used

Three models were implemented and compared:
- **Linear Regression** – for baseline interpretability.
- **Random Forest Regressor** – for handling non-linear relationships and feature importance.
- **XGBoost Regressor** – for enhanced performance and boosting capabilities.

---

## 📊 Features Used

| Feature      | Description                                 |
|--------------|---------------------------------------------|
| `age`        | Age of the insured person                   |
| `sex`        | Gender (male/female)                        |
| `smoker`     | Whether the person is a smoker              |

*Other features were available in the dataset but filtered to focus on the most impactful and interpretable attributes.*

---

## 📁 Project Structure

```
Health-Insurance-Charge-Prediction/
│
├── Health_Insurance_.ipynb         # Jupyter notebook containing the entire workflow
├── insurance.csv                   # Health insurance dataset (Kaggle or similar source)
├── README.md                       # Project overview
└── assets/                         # Optional folder for visualizations or model exports
```

---

## 📈 Workflow

1. **Exploratory Data Analysis (EDA)**
   - Distribution plots for charges, age, and smoker status
   - Correlation matrix and box plots to understand relationships

2. **Data Preprocessing**
   - Categorical encoding (Label Encoding)
   - Feature selection
   - Train-test split

3. **Model Training & Evaluation**
   - Trained and evaluated Linear Regression, Random Forest, and XGBoost models
   - Performance metrics used:
     - R² Score
     - Mean Absolute Error (MAE)
     - Mean Squared Error (MSE)
   - Comparison to determine the best-performing model

4. **Result Interpretation**
   - Visualizations of actual vs. predicted values
   - Feature importance analysis

---

## 📌 Key Insights

- **Smoking status** and **age** are highly correlated with increased insurance charges.
- **XGBoost** outperformed other models, capturing complex relationships in the data.
- Data-driven models enable more equitable and accurate premium pricing.

---

## 💼 Real-World Applications

- **Insurers**: Automate and optimize premium pricing based on risk.
- **Healthcare analysts**: Assess demographic impact on healthcare costs.
- **Policy designers**: Build personalized policy plans using predictive models.

---

## 🛠️ Tech Stack

- **Python**
- **Jupyter Notebook**
- Libraries:
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`
  - `sklearn`, `xgboost`

---

## 🔮 Future Enhancements

- Add more features like BMI, number of children, region, etc.
- Include SHAP for explainable AI insights.
- Build a web app interface using Streamlit or Flask for user interaction.

---

## 📎 Dataset

The dataset is publicly available and commonly used for insurance charge prediction (e.g., from [Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance)).

---

## 🤝 Contributions

Feel free to fork this repo, suggest improvements, or build a live dashboard to make it even more interactive.

---

## 📬 Contact

Project by [@KoreJosh](https://github.com/KoreJosh)  
For feedback or collaboration, reach out via GitHub or open an issue.
