# Customer-Retention-Project
Statistical analysis of customer churn using Chi-Square and T-Test in Python


📊 Customer Churn Analysis Using Statistical Methods
💡 Project Overview

This project analyzes customer churn behavior using real-world telecom data. It applies statistical hypothesis testing to uncover key factors influencing churn and provides actionable insights to help businesses reduce customer loss.
🎯 Objective

To determine which categorical and numerical customer attributes are statistically associated with churn using:

    ✅ Chi-Square Test (for categorical features)

    ✅ T-Test (for numerical features)

📁 Dataset Columns

    Customer Demographics: Gender, Senior Citizen, Partner, Dependents

    Service Features: Internet Service, Online Security, Tech Support

    Billing: Monthly Charges, Total Charges, Payment Method

    Engagement: Tenure, Contract Type

    Target: Churn Label (Yes/No)

🛠 Tools & Technologies

    Python

    Pandas, NumPy

    Seaborn, Matplotlib

    SciPy (for hypothesis testing)

    Google Colab

    GitHub for publishing

📊 Statistical Tests Used
✅ Chi-Square Test

Used to test association between churn and:

    Senior Citizen Status

    Internet Service Type

    Contract Type

    Payment Method

    Gender

Key Finding:

    Contract type, internet service, and payment method are strongly associated with churn (p < 0.05).
    Gender is not significantly associated (p > 0.05).

✅ T-Test

Used to compare averages of churned vs non-churned customers for:

    Tenure

    Monthly Charges

    Total Charges

    CLTV

    Churn Score

Key Finding:

    Churned customers had significantly shorter tenure, higher monthly charges, and lower CLTV (p < 0.05).

📈 Visualizations

    Countplot of churn distribution

    Boxplot of Monthly Charges vs Churn

    Barplots showing Contract Type vs Churn

    Boxplot of CLTV vs Churn

These support the statistical findings with clear visual insights.
🧠 Challenges Faced

    Total Charges column was incorrectly typed as object

    Fixed using pd.to_numeric(errors='coerce') and dropped nulls

    ✅ This demonstrates real-world data cleaning and problem-solving.

📌 Final Takeaways

    Customers on month-to-month contracts are far more likely to churn

    Higher monthly bills and short tenure increase churn risk

    CLTV and churn score are strong churn indicators

    Data-driven strategy can guide retention and targeted offers
