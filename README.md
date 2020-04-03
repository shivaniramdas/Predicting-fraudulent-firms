# Predicting-fraudulent-firms

> This project has been taken up as a research work for a case study of an external government audit company. During audit-planning, auditors examine the business of different government offices but the target to visit the offices with very-high likelihood and significance of misstatements. This is calculated by assessing the risk relevant to the financial reporting goals (Houston, Peters, and Pratt 1999)


## About

The rationale is to build a classification model that can predict the fraudulent firm on the basis of the present and historical risk factors.

There are two csv files : audit_risk and trial to present data. 

The datasets contain information about the sectors and the counts of firms as listed respectively: Irrigation (114), Public Health (77), Buildings and Roads (82), Forest (70), Corporate (47), Animal Husbandry (95), Communication (1), Electrical (4), Land (5), Science and Technology (3), Tourism (1), Fisheries (41), Industries (37), Agriculture (200)

Inherent risk factors

Variable | Definitions
---------|------------
Para A | Discrepancy found in the planned-expenditure of inspection and summary report A in Rs (in crore)
Para B | Discrepancy found in the unplanned-expenditure of inspection and summary report B in Rs (in crore)
Total | Total amount of discrepancy found in otherreports Rs (in crore)
Number | Historical discrepancy score 
Money value | Amount of money involved in misstatementsin the past audits

Control risk factors

Variable | Definitions
---------|------------
Sector score | Historical risk score value of the target-unit using analytical procedure
Loss | Amount of loss suffered by the firm last year
History| Average historical loss suffered by firm in the last 10 years
District score | Historical risk score of a district in the last 10 years

Other factors

Variable | Definitions
---------|------------
Risk | Class assigned to an audit-case
Audit_Risk | Total risk score using analytical procedure
Location ID | Unique ID of the city/province


Several machine learning regressors and classifiers are explored, implemented, and tested to check their applicability in the prediction of the high risk firms. For this we have considered Audit_Risk as the target columns for regression tasks, and Risk as the target column for classification tasks.



## PART 2 - 

Studied dimensionality reduction, evaluation and ensemble techniques and using the same datasets as above, explored the effect of these techniques on the regression and classification models applied before. 
- bagging
- pasting
- adaboost boosting
- gradient boosting
- PCA on data and compared the results before and after applying PCA
- deep learning models
- voting classifiers - one with hard voting and one with soft voting for the classification tasks


