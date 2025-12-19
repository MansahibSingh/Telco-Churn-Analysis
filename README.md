Telecom Churn Prediction – Project Overview

In the highly competitive telecom industry, customer churn significantly impacts revenue, especially since acquiring new customers costs far more than retaining existing ones. This project focuses on predicting churn among high-value prepaid customers in the Indian and Southeast Asian markets, where churn is harder to detect due to the absence of explicit service termination.

Using four months of customer-level data (June–September), churn is defined based on zero usage of calls and mobile internet in the final month. The first two months represent the good phase, the third month the action phase, and the fourth the churn phase. High-value customers are identified as those whose average recharge amount in the first two months falls above the 70th percentile.

The project involves feature engineering, high-value customer filtering, churn labeling, and removal of churn-phase data. Dimensionality reduction using PCA is applied due to high feature dimensionality, followed by training and tuning classification models while addressing class imbalance. Models are evaluated using churn-focused metrics to prioritize accurate identification of potential churners, enabling proactive retention strategies and revenue protection.
