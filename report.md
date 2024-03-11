## Recap of Module 12 Analysis

### Overview

This report offers a comprehensive analysis of machine learning models applied to financial datasets for predicting loan risks. The objective is to assess the performance of two models in categorizing loans as high-risk or low-risk, crucial for effective risk management in the finance sector.

### Objectives

The primary aim of this analysis is to evaluate the efficacy of machine learning algorithms in predicting loan risks based on financial data. Specifically, the focus lies on developing models capable of accurately classifying loans, aiding financial institutions in making well-informed decisions regarding loan approvals and risk mitigation strategies.

### Data Insight

The dataset utilized in this analysis encompasses financial data related to loan repayments, including 75,036 low-risk loans and 2,500 high-risk loans. This dataset serves as the foundation for assessing the performance of the machine learning models, addressing the imbalance within the data to ensure robust model outcomes.

### Methodology

The analysis follows a systematic approach, encompassing data preprocessing, feature selection, model training, and evaluation stages. Two machine learning models are employed: logistic regression as the base classifier and a secondary model integrating resampling techniques to tackle class imbalance effectively.

### Outcome

#### Performance Metrics

##### Machine Learning Model 1:

- Balanced Accuracy Score: Approximately 0.952
- Confusion Matrix: [18,663 True Negatives, 102 False Positives; 56 False Negatives, 563 True Positives]
- Classification Report:
    - Precision
      - Healthy loans (class 0): 1.00
      - High-risk loans (class 1): 0.85
    
    - Recall / True Positive Rate
      - Healthy loans (class 0): 0.99
      - High-risk loans (class 1): 0.91

    - F1-Score
      - Healthy loans (class 0): 1.00
      - High-risk loans (class 1): 0.88

##### Machine Learning Model 2:

- Balanced Accuracy Score: Approximately 0.993
- Confusion Matrix: [18,649 True Negatives, 116 False Positives; 4 False Negatives, 615 True Positives]
- Classification Report:
    - Precision
      - Healthy loans (class 0): 1.00
      - High-risk loans (class 1): 0.84
    
    - Recall / True Positive Rate
      - Healthy loans (class 0): 0.99
      - High-risk loans (class 1): 0.99

    - F1-Score
      - Healthy loans (class 0): 1.00
      - High-risk loans (class 1): 0.91

### Conclusion

The analysis indicates that Machine Learning Model 2 outperforms Model 1 in predicting loan risks. Model 2 demonstrates higher balanced accuracy, improved recall for high-risk loans, and a balanced trade-off between precision and recall. Therefore, Model 2 is recommended for financial institutions seeking to enhance their risk management strategies.

### Recommendations

The selection between models hinges on the specific objectives and priorities of the financial institution. For institutions prioritizing the identification of high-risk loans to minimize defaults, Model 2 is preferable due to its higher recall for high-risk loans. Nonetheless, continual evaluation and refinement of the selected model are essential to ensure its effectiveness and alignment with business objectives. Furthermore, conducting further studies to compare the model's performance against manual risk assessments can offer valuable insights into its efficacy and potential areas for enhancement.