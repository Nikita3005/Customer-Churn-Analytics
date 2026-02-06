# Customer Churn Analytics & Prediction

## Project Overview
Customer churn is a major challenge for subscription-based businesses.  
This project analyzes customer behavior to identify churn drivers and builds a predictive model to help businesses proactively retain high-risk customers.

The focus is on **analytics-driven decision making**, combining exploratory analysis, statistical insights, and a predictive model, with results communicated through a Power BI dashboard.

---

## Business Problem
- Why do customers churn?
- Which customer segments are most at risk?
- How can churn be predicted early to support retention strategies?

---

## Dataset
- Size: **100,000+ customer records**
- Type: Subscription-based customer data
- Key features:
  - Tenure
  - Monthly & Total Charges
  - Contract type
  - Payment method
  - Demographics (Age, Gender)
  - Churn label

*(Raw dataset excluded from repository due to size and licensing constraints.)*

---

## Phase 1: Exploratory Data Analysis (EDA)
- Analyzed churn distribution across customer segments
- Identified strong relationships between churn and:
  - Contract type
  - Customer tenure
  - Monthly charges
- Visualized trends using Python (Seaborn, Matplotlib)

---

## Phase 2: Churn Prediction Model
- Built a **logistic regression model** to predict customer churn
- Performed:
  - Feature encoding
  - Train–test split with stratification
  - Model evaluation using precision, recall, and ROC-AUC
- Interpreted model coefficients to understand churn drivers

### Key Findings
- Customers on **month-to-month contracts** have the highest churn risk
- **Short tenure** strongly increases churn probability
- Higher monthly charges contribute to churn likelihood

---

## Business Recommendations
- Target short-tenure customers with retention offers
- Incentivize upgrades to long-term contracts
- Proactively engage customers with rising monthly charges

---

## Power BI Dashboard
A Power BI dashboard was created as the final storytelling layer to:
- Track churn rate and customer segments
- Visualize churn trends across contracts and tenure
- Support stakeholder decision-making

---

## Tools & Technologies
- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Power BI**: Dashboarding and business storytelling
- **Jupyter Notebook**
- **GitHub**

---


---

## Key Takeaway
This project demonstrates the ability to:
- Analyze large datasets
- Translate data into actionable business insights
- Build and interpret predictive models
- Communicate findings effectively to stakeholders

