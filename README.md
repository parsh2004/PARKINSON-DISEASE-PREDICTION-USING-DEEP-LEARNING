# PARKINSON-DISEASE-PREDICTION-USING-DEEP-LEARNING

### INTRODUCTION

Parkinson's disease (PD) is a progressive neurodegenerative disorder that affects motor and non-motor functions, leading to a significant decline in the quality of life. Accurate and early prediction of disease severity plays a vital role in treatment planning and monitoring disease progression. The Unified Parkinson’s Disease Rating Scale (UPDRS) is a widely used metric to quantify the severity of PD symptoms, enabling clinicians to assess the effectiveness of interventions and disease progression. With the growing availability of telemonitoring datasets and advancements in machine learning, it is now possible to predict disease severity using computational models that analyze clinical and acoustic features.
This project leverages a Long Short-Term Memory (LSTM) model, a type of recurrent neural network, to predict the total UPDRS score using time-series data from the Parkinson’s Telemonitoring dataset. The dataset includes various clinical and acoustic features derived from patients' speech, which are indicative of motor and non-motor symptoms. By employing advanced deep learning and hyperparameter optimization techniques, we aim to enhance the accuracy and reliability of these predictions.

### PROBLEM DEFINITION

Parkinson’s disease (PD) is a progressive neurodegenerative disorder that affects movement control and can significantly reduce the quality of life for patients. Accurate prediction and assessment of disease severity are essential for early intervention, treatment planning, and
 
monitoring disease progression. One key measure of disease severity is the Unified Parkinson's Disease Rating Scale (UPDRS), which quantifies both motor and non-motor symptoms. However, predicting the total UPDRS score and understanding the factors influencing disease progression remain challenging due to the variability of symptoms and individual patient differences.
The goal of this project is to develop predictive models for Parkinson’s disease severity based on a dataset containing both clinical and acoustic features. Clinical features include demographic information such as age and gender, while acoustic features (such as jitter, shimmer, and speech- related measures) provide insight into the motor and non-motor symptoms of PD. The focus is to build and evaluate machine learning and deep learning models that can predict the total UPDRS score, which is used to assess the severity of symptoms in patients. Additionally, hyperparameter optimization will be used to enhance the performance of deep learning models.

### SOFTWARE ENVIRONMENT

* Operating system	: Windows7 (with service pack 1), 8, 8.1 ,10 and 11
*	Language	: Python
*	Jupyter Notebook

### OUTPUT
<img width="495" height="219" alt="image" src="https://github.com/user-attachments/assets/ccc53374-39e4-4b9c-a9c2-a66bcbdc5be9" />

### RESULT
<img width="489" height="181" alt="image" src="https://github.com/user-attachments/assets/373f1eea-1f20-42fe-ad4b-0aef62b8c1d6" />
### CONCLUSION

This project successfully harnessed machine learning and deep learning techniques to predict Parkinson’s disease severity and derive actionable insights into disease progression. The LSTM model, tailored for sequential data, demonstrated impressive accuracy at 93.3%, highlighting its ability to capture temporal relationships critical for modeling neurodegenerative disorders. Complementing this, the Random Forest model effectively utilized non-sequential features, particularly acoustic biomarkers like jitter, shimmer, and HNR, to provide additional perspectives on Parkinson’s severity.Moreover, the exploratory analyses revealed important patterns.Disease Progression Longitudinal tracking of UPDRS scores showcased how symptoms evolve over time, providing a quantitative basis for assessing disease management strategies. Demographic Factors Gender-based analysis uncovered disparities in motor and total UPDRS scores, while age was found to correlate with increased disease severity.Acoustic Biomarkers Acoustic features emerged as significant predictors, indicating their value in non-invasive, early diagnosis and monitoring.
