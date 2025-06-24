# Customer-Retention-Analysis

📊 Executive Summary
This project conducts an in-depth exploratory data analysis (EDA) on a telecom customer base to investigate factors influencing customer churn. The dataset, containing information on customer demographics, subscription details, and service usage, is used to uncover actionable insights that can help reduce churn rates and improve customer retention strategies.

🎯 Objective
The goal of this analysis is to understand why customers leave a telecom service provider (churn) and to identify key demographic and behavioral patterns that differentiate churned customers from retained ones. By visualizing these patterns, the analysis aims to assist business stakeholders in forming data-driven customer retention policies.

📌 Key Insights & Findings
🔺 Overall Churn Rate
Out of the entire customer base, 26.54% of customers have churned, while 73.46% have stayed.

This is visualized using both a countplot and a pie chart, showing a clear minority group of churned customers with potential high business impact.

🧓 Senior Citizen Status
16% of customers are senior citizens.

Among senior citizens, approximately 42% have churned, compared to only 24% among non-senior citizens.

This indicates that senior citizens are 1.75x more likely to churn, suggesting they may require more targeted engagement or support.

📆 Tenure (Length of Subscription)
The highest churn occurs in the first 1–3 months of service.

Customers with tenure > 24 months show a significantly lower churn rate, indicating that long-term engagement builds loyalty.

This insight is supported by a histogram plot, which shows churn density concentrated at lower tenure values.

📄 Contract Type
Customers with month-to-month contracts represent the largest share of churn.

Over 43% of these customers churned.

In contrast, customers with 1-year or 2-year contracts have churn rates of only 11% and 3%, respectively.

The contract duration is one of the most influential churn predictors, as shown in the bar chart comparison.

👩 Gender and Churn
Gender distribution is balanced (roughly 50/50), and churn rates are nearly identical for males and females.

This implies that gender is not a significant factor in churn prediction for this dataset.

📶 Services & Features
Although not fully explored in this version of the notebook, the groundwork is laid for analyzing:

Internet service types (DSL, Fiber, None)

Use of features like Online Security, Tech Support, and Streaming Services

These services are included in the dataset and can offer additional segmentation opportunities for churn analysis.

📈 Visual Storytelling
The project leverages a variety of visual tools to tell the story behind the numbers:

Count plots and pie charts for distribution analysis

Stacked bar charts with embedded percentage labels to highlight segment-wise churn

Histograms to show churn intensity over time (tenure)

Each visualization is tailored for interpretability, helping even non-technical stakeholders grasp key trends instantly.

💡 Business Recommendations
Target Early Churners: Focus retention efforts on customers in their first 3 months of service through onboarding campaigns and special offers.

Promote Longer-Term Contracts: Encourage customers to switch from month-to-month to annual plans with incentives, given the massive drop in churn.

Support Senior Citizens: Develop a customer care program tailored to senior citizens, who show a disproportionately higher churn rate.

Deep-Dive into Optional Services: Extend this analysis to assess the role of optional add-ons (e.g., tech support, online security) in churn behavior.

📂 Conclusion
This analysis provides a data-driven foundation for understanding churn dynamics in the telecom sector. Key factors such as contract type, tenure, and senior citizen status strongly influence churn, while others like gender show limited impact. By acting on these insights, telecom companies can implement more effective retention strategies and personalized service models.
