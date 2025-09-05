# Latest-Project

Project Name : Customer Lifetime Value and Campaign Optimization
End-to-end project simulating how a tech subsciption platform (like Apple Music, iCloud, Microsoft XBox Game Pass) uses Data Science to predict customer value, run experiments and optimize marketing campaigns.

Project Summary:
This project simulates how a global technology subscription platform (similar to Apple Music, iCloud or Microsoft XBox Game Pass) uses Data Science to understand customers, predict future behaviour and optimize marketing campaigns. The goal is to build an end-to-end pipeline that starts with raw customer data, transaction data and campaign data and transforms it into business insights and predictive models. Key tasks include to create analytical dataset in SQL, performing exploratory data analysis, predicting customer lifetime value (LTV) and churn using machine learing and survival analysis, measuring campaign effectiveness through A/B testing and causal inference, and optimizing budget allocation for maximum return on investment. The outputs include predictive models, optimization framework, interactive dashboards, and executive ready reports. This project demonstrates both technical expertise (Python, SQL, ML, pipelines) and business impact (ROI improvement, churn reduction).

Business Goals and Key Performance Indicator:

The primary objective of this project is to customer and campaign data to improve marketing efficiency, increase retention and maximize revenue. Success will be measured using the following business goals and key performance indicators:

1) Predict Customer Value (LTV):
   (a) Estimate each customer's 6-month and 12-month Lifetime value
   (b) KPI: Lifetime Prediction accuracy (R2 >= 0.65 & MAPE <= 25%)

2) Reduce Customer Churn:
   (a) Reduce "At Risk Customers" before they leave
   (b) KPI: Churn Prediction Recall >= 0.80 at 60-day horizon

3) Improve Campaig Targetting:
   (a) Prediction the likellihood of conversion for each customer
   (b) KPI: Propensity model AUC >= 0.85, Top-decile lift >= 3 X Baseline

4) Measure True Campaign Impact
   (a) Use A/B Testing and causal inference to quantify incremental effects
   (b) KPI: Campaign conversion uplift of +10-20% vs control.

5) Optimize Marketing Spend
   (a) Allocate fixed budget across multiple campaigns for the best ROI
   (b) KPI: Reduce reporting time by >= 80%; Adoption by 10+ Stakeholders.

Labels & Horizons:
To evaluate and train models efficiently, the following outcome labels and time horizons are defined:

1) Conversion Lebel:
   Definition: A customer is considered as "converted" if they make a purchase or a subscription within 30 days of campaign exposure.
   Purpose: Used to train Propensity-To-Convert Model

2) Churn Label:
   Definition: A customer is considered as "churned" if they show o activity or cancel their subscription for 60 consecutive days.
   Purpose: Used to build the Churn-Prediction-Model and Survival Analysis.

3) Lifetime Value (LTV) Horizon:
   Definition: Total Customer Value (Spend + Subscription) is calculated over 6-month and 12-month horizons.
   Purpose: Target Variable for the LTV prediction model.

4) A/B Test Evaluation Window:
   Defintion: Campaign Outcomes (conversion, revenue uplift) are posed within 30-days post campaign launch.
   Purpose: Used for A/B Testing and Causal Inference Analysis.

Success Criteria:
This project will be considered successful if the following technical and business benchmarks are achieved:

1) Customer Lifetime Value (LTV) Prediction:
   R-squared >= 0.65
   WAPE (Weighted Absolute Percentage Error) <= 25%
   Spearmark Rank Correlation >= 0.75 (For rank ordering customers by value)

2) Prospensity/Conversion Model:
   ROC-AUC >= 0.85
   Top Decile (10%) of the customers capture >= 3 X Baseline conversion rate
   Precision >= 0.70 at operational recall thresholds

3) Churn Prediction:
   Churn Recall >= 0.80 at 60-day horizon
   Concordance Index (C-index) >= 0.70 for survival model

 4) Campaign Impact (A/B Testing & Causal Interface):
    Statistically Significant Uplift (95% Confidence) in conversion or revenue
    Campaign Conversion Uplift of +10-20% vs. control group

5) Marketing Spend Optimization:
   ROI improvement of +15-25% compared to naive baseline allocation
   Customer Aquisition Cost (CAC) reduced by >= 10%

6) Operational and Reporting Efficiency:
   Automated pipelines reduce reporting time by >= 80% (Eg. 2 hours --> <20 minutes)
   Dashboard adopted by >= 10 stakeholders (business and technical users)
    
