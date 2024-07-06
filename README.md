# Stroke Prediction
 Comparison of Various Computational Models and Interpretation using LIME and SHAP kernels

 Stroke is one dangerous illness that kills people. Across the globe, it is among the main causes of mortality and disability. It requires early identification and precise measures to be taken in order to prevent stroke and further damages to the brain and other parts of body. Here I have investigated the use of machine learning techniques that includes Random Forest, K- Nearest Neighbors (KNN), Support Vector Machine (SVM), Decision Tree Classifier, Random Forest Classifier, Naive Bayes and multiple Boosting Classifiers. 

 The "Healthcare Dataset Stroke Data" is the dataset used, which is preprocessed and then trained upon ML models. For Random Forest Classifier, the maximum accuracy observed was 94.91%, and upon Hyper parameter Tuning- there was rise in accuracy to 95.64%. Evaluation criteria like F1-score, precision, and recall provides additional evidence for the effectiveness of these models.
 
 Further in order to explain how each feature contributes differently to each prediction I have employed two popular techniques for XAI, LIME and SHAP. LIME and SHAP provides local, interpretable explanations and global explanations respectively.