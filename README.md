
## 🧠 Objectives

- Understand the distribution of churn in the dataset
- Identify high-risk customer segments
- Analyze service usage patterns and payment behavior
- Derive actionable insights to reduce churn

## 🔍 Key Insights

- **Churn Rate**: Overall churn is **26.54%**.
- **High-Risk Groups**:
  - Senior citizens churn more (42.4%) than non-senior citizens (24.3%).
  - Customers with 1–2 months of tenure churn at over 60%.
- **Contract Type Impact**:
  - Month-to-month: 43.9% churn
  - One-year: 11.5% churn
  - Two-year: 2.8% churn
- **Service Usage Trends**:
  - Fiber Optic Internet users churn more (41.9%) than DSL users (18.9%).
  - Online security features reduce churn significantly.
- **Payment Methods**:
  - Electronic Check users churn at 45.3%.
  - Other methods like Credit Card and Bank Transfer have much lower churn rates.

## 📌 Recommendations

- Improve onboarding and early engagement (first 2–3 months)
- Promote longer-term contracts with benefits
- Encourage value-added services (OnlineSecurity, TechSupport)
- Address Fiber Optic service issues
- Transition users from Electronic Check to other stable payment options

## 📦 Dependencies

- Python 3.8+
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook

You can install the dependencies using:
```bash
pip install -r requirements.txt
