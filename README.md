# Risk_Assesment_Machine_Learning
## Purpose

A company that provides peer-to-peer loans aims to improve their loan application process. They want to leverage machine learning to accurately predict the creditworthiness of borrowers. This will help them:

Speed up the loan application process: By automating risk assessment.
Improve loan decision accuracy: By better identifying low-risk borrowers.
Enhance the borrower experience: By providing faster and more reliable loan decisions.
To achieve this, the company needs assistance in:

Developing and evaluating various machine learning models.
Addressing imbalanced data: By implementing oversampling and undersampling techniques.
Measuring model performance: To determine the most effective model for predicting credit risk.
By implementing these steps, the company expects to significantly enhance their loan portfolio and minimize potential losses.

## Output Summary
Among the tested models, undersampling with the Cluster Centroids algorithm resulted in the lowest balanced accuracy (0.55). All models exhibited low precision in predicting high-risk borrowers.

The Balanced Random Forest and Easy Ensemble classifiers achieved the highest recall scores, indicating their ability to identify both high-risk and low-risk borrowers effectively.

The Easy Ensemble Classifier is recommended due to its superior balanced accuracy (0.93). However, it's crucial to acknowledge the low precision score (0.09) for high-risk predictions, implying that a significant portion of the predicted high-risk borrowers might actually be low-risk.


