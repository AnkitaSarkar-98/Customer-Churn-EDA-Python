# Retaining Growth: Reversing Churn to Protect Revenue

## Overview
This project provides an Exploratory Data Analysis (EDA) on customer churn to uncover key drivers behind customer drop-off and identify actionable retention strategies. Analyzing a dataset of 7,043 customers reveals an overall churn rate of 26.54% with an average monthly charge of $64.76. The primary goal is to help businesses reverse churn and protect recurring revenue through data-backed insights[.

### Key Findings
* **Contract Commitment:** Customers on Month-to-Month contracts exhibit a significantly higher churn proportion compared to those on 1-year or 2-year plans.
* **Support Friction:** A higher volume of technical support tickets strongly correlates with increased churn risk.
* **Price Sensitivity:** Churned users show a heavy concentration around higher monthly charges ($70–$100 range).
* **Tenure Vulnerability:** Churn is heavily front-loaded in the 0–1 year tenure cohort, with retention stabilizing after 2 years.

## Tools & Technologies
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Seaborn, Matplotlib

## Methods & Workflow
1. **Data Preprocessing & Cleaning:**
   * Handled missing values by converting total charges to numeric formats and imputing missing records with median values.
   * Encoded categorical targets like `Churn` into numeric indicators for correlation modeling.

2. **Exploratory Data Analysis (EDA):**
   * **KPI Calculation:** Summarized overall customer loss, retention percentages, and revenue baseline metrics.
   * **Categorical Feature Analysis:** Evaluated churn rates across demographic segments (senior citizens, dependents), internet service types (fiber optic vs. DSL), and payment methods (electronic checks).
   * **Numerical Distribution & Correlation:** Used Kernel Density Estimation (KDE) plots and Seaborn heatmap matrices to measure relationships between tenure, monthly charges, support tickets, and churn rates.

3. **Cohort & Risk Segmentation:**
   * Grouped customer tenures into multi-year cohorts to track drop-off timing across the customer lifecycle.

## Conclusion & Strategic Recommendations
* **Incentivize Long-Term Contracts:** Offer discounts or bundled perks to transition high-risk Month-to-Month subscribers onto 1-year or 2-year commitments.
* **Optimize Early Onboarding:** Implement proactive retention triggers during the first 12 months to improve initial customer retention.
* **Proactive Support Resolution:** Automatically flag accounts with multiple tech support tickets for priority resolution to reduce service-related cancellations.

---

Thank you for taking the time to check out this project! Your interest, feedback, and contributions mean a lot. If you have any suggestions feel free to share. Don't forget to ⭐ this repository if you found it helpful it really helps others find it too.
Happy coding!
