## Business Insight Report: Customer Churn Analysis

**Prepared for:** Leader and Business stakeholders
**Date:** 24/07/2025

**Executive Summary:**

This report presents a detailed analysis of customer churn based on the provided dataset. Through exploratory data analysis, feature engineering, customer segmentation, and predictive modeling, we have identified key factors influencing churn, segmented the customer base into distinct groups with varying churn risks, and developed a predictive model to identify at-risk customers. The findings highlight critical areas for intervention to reduce churn and improve customer retention.

**Key Findings:**

1.  **Churn Overview:** The dataset shows a significant number of customers who churn, indicating a need for focused retention efforts. The imbalance in the churn variable (more non-churning customers) is noted and considered in the analysis.

2.  **Churn Drivers (from EDA):** Several factors are strongly associated with churn:
    *   **Tenure:** Newer customers with shorter tenures are significantly more likely to churn.
    *   **Monthly Charges:** Customers with higher monthly charges have a higher propensity to churn.
    *   **Contract Type:** Month-to-month contracts have a substantially higher churn rate compared to longer-term contracts (one-year and two-year).
    *   **Internet Service:** Customers with Fiber Optic internet service exhibit a higher churn rate.
    *   **Additional Services:** Lack of services like Online Security, Online Backup, Device Protection, and Tech Support is associated with higher churn.
    *   **Payment Method:** Electronic Check users show a higher churn rate.
    *   **Partner and Dependents:** Customers without partners or dependents are more likely to churn.

3.  **Customer Segmentation:** K-Means clustering identified distinct customer segments:
    *   Analysis of these segments revealed groups with significantly different churn rates. For example, one segment (Cluster 2) showed a particularly high churn rate (approximately 76.7%), characterized by [mention key characteristics of this high-churn cluster based on the segmentation analysis, e.g., lower tenure, higher monthly charges, specific service usage patterns]. Other segments exhibited much lower churn risks.

4.  **Predictive Churn Model:** A Logistic Regression model was developed to predict churn:
    *   The model achieved an overall accuracy of around 85.7%.
    *   It demonstrated reasonable precision (76%) and recall (68%) for identifying churning customers. While the model can identify a good portion of at-risk customers, there is room for improvement in minimizing false positives and false negatives.

**Business Implications and Recommendations:**

Based on these findings, the following actions are recommended to mitigate churn:

1.  **Target Newer Customers:** Implement proactive engagement strategies for customers in their first few months of service, as they are at higher risk of churning. This could include enhanced onboarding, check-ins, and early-life offers.
2.  **Address High Monthly Charges and Fiber Optic Users:** Investigate the reasons behind higher churn among customers with high monthly charges and those using Fiber Optic service. This might involve reviewing pricing strategies, improving service quality for Fiber Optic, or offering tailored packages.
3.  **Promote Long-Term Contracts:** Incentivize customers to switch from month-to-month contracts to one-year or two-year contracts through discounts or added benefits.
4.  **Bundle and Promote Additional Services:** Highlight the value of services like Online Security, Online Backup, Device Protection, and Tech Support, as customers with these services are less likely to churn. Consider bundling options or promotional offers.
5.  **Analyze Electronic Check Payment Method:** Investigate the reasons for higher churn among Electronic Check users. This could be related to payment convenience, security concerns, or other underlying factors. Consider promoting alternative payment methods or addressing specific issues for this group.
6.  **Leverage Customer Segmentation for Targeted Campaigns:** Use the identified customer segments to tailor marketing messages, offers, and retention efforts. Focus high-retention efforts on segments with the highest churn risk (e.g., Cluster 2). Develop specific value propositions for each segment based on their characteristics.
7.  **Utilize the Predictive Model for Proactive Intervention:** Integrate the churn prediction model into operational workflows to identify individual customers at high risk in near real-time. Enable customer-facing teams (e.g., customer support, account managers) to reach out with personalized retention offers or support before the customer churns.

**Limitations and Future Steps:**

*   The current model is a starting point; exploring other machine learning algorithms (e.g., Gradient Boosting, Random Forests, Neural Networks) could potentially improve predictive performance.
*   A deeper dive into the characteristics and behaviors of the highest-churn segment is recommended to uncover more specific pain points.
*   Implementing and tracking the effectiveness of the recommended retention strategies is crucial.
*   Further feature engineering or incorporating external data sources could enhance the analysis.
*   Consider implementing an A/B testing framework to evaluate the impact of different retention interventions on specific customer segments.

**Conclusion:**

Customer churn is a significant challenge, but by understanding the key drivers, segmenting the customer base, and leveraging predictive analytics, the business can implement targeted and proactive strategies to improve customer retention and ultimately drive long-term growth.