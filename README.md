# Ecig-Sleep-Project
This project investigates the association between e-cigarette use and inadequate sleep (<7 hours per night) using complex survey data and SAS programming. The analysis is based on a BRFSS-like dataset and employs PROC SURVEYLOGISTIC to account for survey weights, stratification, and clustering. The project includes data cleaning, recoding, descriptive statistics, and both unadjusted and adjusted logistic regression models.

🔧 Tools Used:
SAS (Statistical Analysis System)

Complex Survey Procedures: PROC SURVEYFREQ, PROC SURVEYLOGISTIC

Public Health Dataset (structured like BRFSS)

🔍 Research Objective:
To examine whether e-cigarette use is independently associated with increased odds of inadequate sleep after adjusting for demographic and behavioral confounders.

The main goal of this analysis was to evaluate the association between e-cigarette use and inadequate sleep (defined as fewer than 7 hours per night). We used weighted logistic regression models appropriate for complex survey data.

🔹 Unadjusted Model
Odds Ratio (OR) for e-cigarette use: 1.089

95% Confidence Interval: 0.996 – 1.191

Interpretation: E-cigarette users had slightly higher odds of reporting inadequate sleep, but this association was not statistically significant since the confidence interval includes 1.

🔹 Adjusted Model
After controlling for multiple confounding variables (age category, checkup history, alcohol consumption, education, employment status, ethnicity, general health, marital status, and sex):

Adjusted Odds Ratio (AOR) for e-cigarette use: 1.026

95% Confidence Interval: 0.933 – 1.127

Interpretation: Once adjusted for other risk factors, the relationship between e-cigarette use and inadequate sleep was further reduced and remained not statistically significant.

🔍 Additional Significant Predictors of Inadequate Sleep
The following factors were statistically significant predictors in the adjusted model:


Age Category (Older vs. Youngest). Older individuals were less likely to report inadequate sleep
Checkup	(No checkup vs. Yes). Regular medical checkups were associated with better sleep
Education	(Higher vs. Lower). Higher education level was associated with slightly worse sleep
Employment (Unemployed vs. Employed). Unemployed individuals had higher odds of inadequate sleep
Ethnicity (AA	vs. White).	AA had significantly worse sleep
Ethnicity (Asian	vs. White). Asian also showed higher sleep risk
General Health.	Better general health correlated with better sleep
Marriage	(Not married vs. Married). Married individuals reported slightly better sleep
Sex	(Female vs. Male). Females were less likely to report inadequate sleep
