# Customer Segmentation Analysis
                                ![1_oEu4EK58DQTlkZtW_toDOg](https://github.com/user-attachments/assets/9d1ed18c-0fbc-4a57-9756-bd2eb675165a)



## Overview
This analysis segments customers based on their **Age**, **Income**, and **Spending Score**. The goal is to identify distinct customer segments for targeted marketing strategies.

## Data Summary:
The dataset contains **1,00+ rows** with customer data, including their demographic information and spending habits. The data was clustered into **5 segments** using the **K-Means** algorithm.

### Key Findings:

- **Cluster 0 (18.0%)**: High-income, moderate spending — Target with **personalized promotions** to drive higher spending.
- **Cluster 1 (11.5%)**: Low spending, medium income — Use **personalized offers** to boost spending.
- **Cluster 2 (39.5%)**: High spending, low income — Offer **budget-friendly options** and **loyalty programs** to retain engagement.
- **Cluster 3 (11.5%)**: Young, low spending — Provide **incentives** and **first-purchase rewards** to increase loyalty.
- **Cluster 4 (19.5%)**: High income, high spending — Prioritize with **exclusive offers** and **premium products** to maximize profitability.

## Segmentation Impact:
- **Targeted Marketing**: Identified customer groups with distinct behavior patterns to tailor promotional efforts.
- **Improved Customer Engagement**: Focused on high-value customers with **low spending** for increased engagement.

## Evaluation:
- The segmentation quality was validated using **Silhouette Score** and **DB Index**, with scores of:
  - **Silhouette Score**: 0.55 (indicating good cohesion within clusters).
  - **DB Index**: 0.48 (indicating a relatively low overlap between clusters).

## Tools Used:
- **K-Means Clustering**: For segmentation.
- **Scikit-learn**: For clustering and evaluation.
- **Matplotlib/Seaborn**: For visualizing clusters and trends.

## Conclusion:
This segmentation analysis provides valuable insights for targeted customer strategies, improving marketing efforts, and optimizing customer engagement.

