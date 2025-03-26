# Employee Attrition Analytics Project - README File

<em>This is an independent HR Analytics project exploring employee attrition, particularly using synthetic HR data produced by IBM Data Scientists. The link to the dataset can be found on [Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset/data). The project comprises the following parts:</em>

<b> Part I - Statistical Insights & Predictions </b>
1) Data Preprocessing, Chi-Square Analysis, & Logistic Regression
2) Decision Trees, XGBoost

Summary Model Performance (F1-Score):
- Logistic Regression: 86.32 %
- Decision Trees: 92.72 %
- <b>XGBoost: 96.28 %</b>

<b> Part II - Data Visualization using Microsoft Power BI </b>

Key Takeaways from the PowerBI Report:
  - <b>Average Attrition Rate: 16.12 %</b> --> While the ideal scenario is for an organization to have an attrition rate that is less than 10% annually, an unsually high attrition rate is anything above 20%. Given our findings for this dataset, I believe the People & Culture team should re-evaluate their people strategy. Such attrition rate may be an indication of poor leadership, inadequate compensation, low employee engagement, etc.
  - When it comes to metrics like job satisfaction, environment satisfaction, work-life balance score, and performance rating, the highest score awarded is 4 (not sure if the highest is 5 and no employee awarded that score or if the highest score on the scale is 4). If the highest score on the scale is 4, the average performance rating is good but could be better (78.75%). On the other hand, job satisfaction, environment satisfaction, and work-life balance scores need some attention (~ 68% - 69%)

<u>The top 5 key influencers identified by the Key Influencers Visual were:</u>
  1)  Job Role Being Sales Representative
        *  I noticed that this job role has one of the lowest average monthly incomes among all the job roles
  2)  Average Tenure Being 1 Year or Less
  3)  Average Monthly Income Being $ 2800 or Less
  4)  Employees Categorized in Job Level 1 (Lowest Job Level Category)
  5)  Employees with Stock Option Level of 0 (No Stock Options)
         
  -  These key influencers are consistent with the significant predictors identified by the Chi-Square Test Analysis done earlier in Notebook 1. The only key influencer that was not identified as 'signficiant' by the Chi-Square Test Analysis is <em>Monthly Income</em>
