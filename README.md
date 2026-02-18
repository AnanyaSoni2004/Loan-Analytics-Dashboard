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







## Analysis Suggestions







## Data Cleaning Notes
*Handled missing values using median, mode, and band-based imputation techniques.
*Recalculated dependent financial variables such as Loan-To-Value Ratio (LTV).
*Standardized categorical labels and numerical formats for consistency.
*Created derived analytical features including Risk Score and Band classifications.
*Preserved financial relationships between Loan Amount, Property Value, and LTV.
*Validated calculated fields to ensure analytical accuracy.

## Dashboard
<img width="1348" height="1293" alt="image" src="https://github.com/user-attachments/assets/f116a89c-05c7-457c-963d-7e5472506ca9" />
