# Loan Analytics Dashboard

## Project Overview
This dataset contains structured bank loan records designed to analyze lending patterns, borrower risk characteristics, and loan performance behavior.
It is provided in a raw and partially uncleaned format to offer hands-on experience with real-world financial data preprocessing, analysis, and dashboard development.



## File Details

* **File name** : loan_dataset.csv
* **Total Records** : 10,000

## Data Dictionary
| **Column Name** | **Description** | **Data Type**|
|-------------|-------------|----------|
|**ID**    | Unique identifier  | Integer|
|**Income**	    |Borrower income|	Integer|
|**Year**	|Year of loan record|	Integer|
|**Loan_Amount**|	Total loan value|	Integer|
|**Rate_Of_Interest**	|Borrower creditworthiness metric|	Float|
|**Credit_Score**|	Total distance driven (in km)|	Integer|
|**Debt_To_Income_Ratio**|	Borrower repayment capacity indicator |	Float|
|**Loan_To_Value_Ratio**|	Loan exposure relative to collateral |	Float|
|**Loan_Type**|	Loan product category	|Categorical|
|**Loan_Purpose**|Intended use of loan|	Text|
|**Risk Score**|	Derived borrower risk metric|	Integer|
|**Region**|	Geographic classification	|Text|
|**Interest_Only**|	Interest-only loan indicator|	Float|
|**Status**|	Loan performance indicator |Integer|

## Key Insights & Statistics

### Portfolio Risk Drivers
- Default probability increases significantly as **Debt-to-Income (DTI) ratios rise**, indicating borrower affordability is a primary risk driver.
- Loans with **high Loan-to-Value (LTV)** ratios show noticeably higher default concentrations due to reduced collateral buffers.
- **Lower credit score segments** consistently demonstrate higher default rates, reinforcing creditworthiness as a core determinant of loan performance.

### Portfolio Composition
- A measurable share of loans falls into **medium-to-high risk categories**, suggesting concentration risk within certain borrower segments.
- **Interest-only loans** represent a structurally higher-risk segment due to delayed principal repayment exposure.
- Certain **loan purposes dominate portfolio volume**, creating potential exposure concentration in specific lending categories.

### Regional & Product Patterns
- Loan performance varies significantly by **region**, indicating geographic differences in borrower behavior and default risk.
- **Loan type variation** reveals that product design influences repayment behavior and risk levels.

### Key Portfolio Indicators
- Strong positive relationship between:
  - High DTI → higher defaults  
  - High LTV → higher defaults  
  - Low credit score → higher defaults  
- Financial ratios (**DTI, LTV, Credit Score**) are the primary predictors of portfolio risk exposure.

---

## Analysis Suggestions

### Risk Monitoring & Strategy
- Implement **DTI-based screening thresholds** to reduce high-risk approvals.
- Strengthen **LTV controls** to improve collateral coverage and reduce exposure.
- Monitor and cap **interest-only loan share** within the portfolio.

### Borrower Segmentation
- Use **credit score bands, DTI bands, and LTV bands** for targeted risk segmentation.
- Identify high-risk clusters and apply stricter approval or pricing policies.

### Regional Optimization
- Track **default rate by region** to detect geographic risk concentration.
- Adjust lending strategies region-wise to balance growth and risk.

### Portfolio Optimization
- Diversify loan purpose distribution to reduce concentration risk.
- Use dashboard KPIs to continuously track:
  - Default rate  
  - High-risk borrower ratio  
  - Average credit score  
  - Interest rate trends  

### Future Enhancements
- Add predictive modeling for default probability.
- Introduce automated risk scoring.
- Integrate real-time monitoring dashboards.
- Incorporate macroeconomic indicators for deeper analysis.

## Data Cleaning Notes
*Handled missing values using median, mode, and band-based imputation techniques.
*Recalculated dependent financial variables such as Loan-To-Value Ratio (LTV).
*Standardized categorical labels and numerical formats for consistency.
*Created derived analytical features including Risk Score and Band classifications.
*Preserved financial relationships between Loan Amount, Property Value, and LTV.
*Validated calculated fields to ensure analytical accuracy.

## Dashboard
Here is the Dashboard:
<img width="1348" height="1293" alt="image" src="https://github.com/user-attachments/assets/f116a89c-05c7-457c-963d-7e5472506ca9" />
