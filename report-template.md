# Module 12 Report Template

## Overview of the Analysis

Credit Risk Analysis Report :
Overview:The purpose of this analysis is to develop and evaluate a machine learning model to assess the 
    creditworthiness of borrowers using historical lending activity data from a peer-to-peer lending services 
    company. The goal is to build a model that can effectively predict whether a loan is at high risk of 
    defaulting or not.
    
    Model Evaluation Metrics:
        •Accuracy Score: The accuracy of the model in predicting both healthy and high-risk loans.
        •Precision Score: The percentage of correctly predicted high-risk loans out of all predicted high-risk loans.
        •Recall Score: The percentage of correctly predicted high-risk loans out of all actual high-risk loans.
            
    Model Performance:
        •Accuracy Score: The original logistic regression model achieved an accuracy score of 0.99 on the testing data. 
            The resampled logistic regression model also achieved an accuracy score of 0.99.
        •Precision Score (High-Risk Loans):
            Original Model: 0.85
            Resampled Model: 0.84
        •Recall Score (High-Risk Loans):
            Original Model: 0.91
            Resampled Model: 0.99
                
    Summary and Recommendations: 
        Both the original and resampled logistic regression models exhibited outstanding performance in predicting credit risk. 
        Here are the key takeaways:
            
        Accuracy: Both models achieved a high accuracy of 0.99, indicating their ability to correctly predict the majority of loan statuses.
        Precision: The precision score for predicting high-risk loans is relatively high for both models. The original model achieved a precision 
            of 0.85, and the resampled model achieved a precision of 0.84. This means that when the models classify a loan as high risk, they are 
            correct about 84% to 85% of the time.
        Recall: The resampled model significantly outperformed the original model in terms of recall for high-risk loans. The original model achieved
            a recall of 0.91, while the resampled model achieved a remarkable recall of 0.99. This indicates that the resampled model can effectively 
            identify almost all actual high-risk loans.
    Given the excellent accuracy, precision, and recall scores achieved by both models, it is recommended that the company use the resampled logistic 
    regression model for assessing credit risk. The resampled model provides a more balanced performance by effectively capturing high-risk loans while 
    maintaining high precision for both classes. Its high recall score suggests it's reliable in identifying loans with a high risk of default, which 
    is crucial for mitigating potential losses. Therefore, the resampled logistic regression model is well-suited for practical use in the company's 
    credit assessment process.
