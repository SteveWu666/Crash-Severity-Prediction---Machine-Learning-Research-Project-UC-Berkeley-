# Crash Severity Prediction  
**Machine Learning Research Project — UC Berkeley (INDENG 242A)**

## Overview
This project applies supervised machine learning techniques to predict road crash severity in Montgomery County. We evaluate six models—Logistic Regression, Decision Tree, Random Forest, Bootstrap Aggregating (Bagging), AdaBoost, and XGBoost—to classify crashes into three categories: Fatal, Injury, and Property Damage.

## Dataset
- Source: [Crash Reporting - Drivers Data (Montgomery County)](https://data.montgomerycountymd.gov/Public-Safety/Crash-Reporting-Drivers-Data/mmzv-x632)
- Size: 188,800 records, 39 features  
- Features include crash time, weather, road type, surface condition, lighting, and vehicle/driver details.

## Methodology
- **Data Preprocessing**: Cleaning, outlier removal, SMOTE for class imbalance, z-score normalization.
- **Feature Engineering**: Domain-driven and model-specific selection.
- **Models**: Trained and compared across multiple metrics (accuracy, precision, recall, F1, ROC-AUC).
- **Best Performer**: Random Forest achieved 75.8% accuracy and consistent performance across all metrics.

## Key Findings
- Severe crashes are more likely in normal weather and poor lighting.
- Fatal crashes occur disproportionately in high-speed zones (>35 mph).
- Majority of fatal crashes happen during nighttime, despite presence of lighting.

## Team
- Jim Cao  
- Corey Lin  
- Qilian Wu  
- Derek Shih  
- Jingwen Zhang  
- Advisor: Prof. Ying Cui

## License & Disclaimer
This project is the joint work of the authors listed above, developed as part of a research course at UC Berkeley.

**Copyright © 2024**
**Jim Cao, Corey Lin, Qilian Wu, Derek Shih, Jingwen Zhang**

All rights reserved.  
This work is provided strictly for academic reference and personal learning purposes. Any redistribution, modification, commercial use, or unauthorized publication is prohibited without explicit written permission from all contributors.

Plagiarism in any form will constitute a violation of academic integrity and copyright.

## Contact
For citation or permission requests, please contact any of the contributors via institutional email.