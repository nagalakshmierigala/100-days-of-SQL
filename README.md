# Spam Detection Project Overview
This project aims to classify SMS messages as spam or ham using the SMS Spam Collection dataset. The focus is on overcoming dataset imbalance to achieve high accuracy in spam detection.

# Dataset:
The dataset comprises messages labeled as 'ham' (legitimate) or 'spam', with a notable imbalance favoring ham messages. Columns have been renamed to 'label' and 'message' for clarity.

# Evaluation Metric:
Due to the imbalanced dataset, the F1 score, alongside Precision and Recall, was chosen as the primary evaluation metric.

# Methodology:
**Classification Pipelines:** Evaluated three pipelines: TF-IDF, Feature Engineering, and a combination of both.
**Model Selection and Tuning:** Experimented with Logistic Regression, focusing on tuning for imbalance. RandomizedSearch was used for efficient hyperparameter tuning.

# Results:
The final model demonstrated high performance, achieving a precision of 99% for ham and 96% for spam, with recall rates of 99% for ham and 94% for spam. The overall accuracy stood at 99%, showcasing the model's ability to accurately classify spam and ham messages in an imbalanced dataset.

# Conclusion:
The project successfully developed a robust model for SMS spam detection, highlighting the effectiveness of combining feature engineering with advanced machine learning techniques. Future work will explore further improvements in feature selection and model optimization.
