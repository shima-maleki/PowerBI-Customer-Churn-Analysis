# 📊 Telecom Customer Churn Prediction & Retention Strategy
This project focuses on identifying customers who are likely to churn from a telecom company and delivering actionable insights to improve customer retention. It encompasses a full data science lifecycle — from data cleaning and exploratory analysis to predictive modeling and dashboard development.

## 📊 Dashboard

![Chrun DashBoard](visuals/churn_dashboard.png)
![Chrun Risk Analysis](visuals/chrun_risk_analysis.png)

**A Power BI dashboard was built to present:**

- High-churn-risk segments

- Key churn drivers (e.g., contract type, customer tenure)

- Trends by region, plan type, and services used

- Recommended actions based on model insights

[Report](Report/report.md)

**💡 The dashboard empowers non-technical stakeholders to make informed retention strategies through intuitive visual analytics.**

## 🔍 Objective
To develop a data-driven solution that predicts customer churn with high accuracy and provides business stakeholders with interpretable insights to guide strategic decisions.

## 🧠 Key Highlights
**End-to-End Data Science Pipeline:** Data preprocessing, feature engineering, model training, and evaluation using Python and Jupyter Notebooks.

**Machine Learning:** Developed and deployed predictive models to identify churn risk.

**Business Insights:** Extracted actionable recommendations based on model outputs and customer behavior patterns.

**Dashboarding:** Created a Power BI dashboard for non-technical stakeholders to interact with the insights visually.

## 🗂️ Project Structure
```
POWERBI-CUSTOMER-CHURN-PROJECT/
│
├── dashboard/
│   └── Customer Risk Analysis Dashboard.pbix         # Power BI dashboard file
│
├── data/
│   ├── raw/
│   │   └── Customer-Churn-Dataset.xlsx               # Original dataset
│   └── processed/
│       ├── Clean_Customer-Churn-Dataset.csv          # Cleaned dataset
│       └── final_Customer-Churn-Dataset.csv          # Feature-engineered dataset
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb                        # Missing values, data types
│   ├── 02_exploratory_analysis.ipynb                 # Visual and statistical EDA
│   ├── 03_feature_engineering.ipynb                  # Encoding, scaling, new features
│   ├── 04_model_training.ipynb                       # ML models, metrics, tuning
│   └── 05_business_insights.ipynb                    # Interpreting model for business
│
├── scripts/
│   └── churn_predictor.py                            # Inference script
│
├── visuals/
│   └── churn_dashboard.png                           # Static preview of dashboard
│
├── churn_app.py                                      # (Optional) Streamlit/Flask app
├── LICENSE
├── README.md
├── requirements.txt                                  # Python dependencies
└── .gitignore
```

## 🧰 Technologies & Tools

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

- Jupyter Notebooks

- Power BI for business reporting

- Git & GitHub for version control

- Streamlit / Flask (Optional web deployment)

- Excel for raw data validation

## 📈 Machine Learning Approach
**Data Analysis**

![Data Analysis](visuals/image.png)

**Supervised Learning Model:**

- Logistic Regression - For predicting Chrun

**Un-supervised Learning Models:**

- KMeans Clustering for Clustering groups

- PCS for Cluster Visualisation

![PCA Visual](visuals/PCA.png)

**Model Evaluation Metrics:**

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

![Confusion_Matrix](visuals/confusion_matric.png)

**Feature Engineering:**

- 'AverageMonthlyCharge' added feature

- Feature scaling (MinMax)

- Correlation analysis for multicollinearity removal

![](visuals/pairplot.png)

## 🧠 Business Insights
Some of the actionable insights derived include:

- The customer churn rate last month was 27%, which means that out of 7043 customers, 1869 left the company.

- The length of the contract and the tenure of the customer are key factors in predicting the churn behavior. Customers who have a monthly contract and a lower tenure are more likely to switch to other providers.

- Customers who do not have any dependents or partners are more prone to churn than those who do.

- Gender does not seem to have a significant impact on the churn decision. However, senior citizens are less likely to churn than non-senior citizens.

- Customers who use Fibre Optic internet service have a higher churn rate than those who use other types of internet service. The payment method also influences the churn decision, with Electronic check being the most common among the churned customers.

- Customers who do not receive services such as Tech Support, Device Protection, and Online Security are more dissatisfied and tend to look for other options.

These insights were derived through both statistical exploration and model interpretability techniques (e.g., SHAP values, feature importance).

## 🚀 Communication & Storytelling
This project emphasizes clear communication of technical findings through:

- Well-documented notebooks

- Clean and modular code

- Visual storytelling via Power BI

- Summarized insights and recommendations in plain business language

## 📄 Why This Project Matters to Employers
- Demonstrates ability to solve real-world business problems using data

- Shows proficiency across the entire data science workflow

- Reflects strong communication skills, with a focus on explaining technical outputs to business users

- Integrates data visualization and storytelling into model-driven decision-making

- Applies clean coding practices and project structure, making it scalable and reusable

## ✅ How to Reproduce
Clone the repo:
```
git clone https://github.com/yourusername/telecom-churn-project.git
cd telecom-churn-project
```

Install dependencies:

```
pip install -r requirements.txt
```

**Launch notebooks or run scripts:**

- jupyter notebook
- Open Power BI file from the dashboard folder to explore visual reports.

## 🤝 Let's Connect
[LinkedIn](https://www.linkedin.com/in/malekishima/)

If you're a recruiter, hiring manager, or collaborator interested in data science, analytics, or machine learning — I’d love to connect.

Feel free to explore my other projects or reach out!