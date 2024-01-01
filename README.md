# Stroke-Prediction

The model predicts whether a patient is likely to have a stroke based on various input parameters such as gender, age, presence of hypertension, presence of heart disease, marital status, work type, residence type, average glucose level, BMI (body mass index), and smoking status. The dataset contains patient information, and the task is to develop a model that can accurately classify patients as either having a stroke (1) or not having a stroke (0) based on the provided features.

### 👩‍💻 Dataset -
https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

### 📌 The following Tasks are completed -
1. Are there any missing values in the dataset? If so, how will you handle them? What is the distribution of the stroke variable? Are there an equal number of patients with and without strokes?
2. How does the distribution of stroke vary with respect to gender, age, hypertension, heart disease, ever-married status, work type, and residence type?
3. How does the occurrence of stroke vary across different smoking statuses? Visualize it using a bar plot or stacked bar plot.
4. Can you identify any outliers in the dataset, particularly for numerical features like age, average glucose level, and BMI? How are you planning to handle them?
5. Are there any correlations between the different features and the presence of a stroke? Visualize it using a heatmap or correlation matrix? Determine if any feature(s) can be dropped based on their relationship with the target variable?

## EDA


<img width="588" alt="Screenshot 2024-01-01 232627" src="https://github.com/Ishaswm/Stroke-Prediction/assets/122556303/8314e0e5-75ef-4429-ba25-82f5346f38ff">
<img width="459" alt="Screenshot 2024-01-01 232510" src="https://github.com/Ishaswm/Stroke-Prediction/assets/122556303/96ac048d-7d6d-459d-ad0f-14374d46210d">

## MODEL
1. **sklearn.model_selection** for performing cross-validation on a given model.
2. **sklearn.linear_model** for logistic regression models.
3. **RandomForestClassifier** from sklearn.ensemble 
4. SVC from sklearn.svm for **Support Vector Classification models**.
5. Evaluation metrics from sklearn.metrics:
i) accuracy_score: Computes the accuracy classification score.
ii) precision_score: Computes the precision of the model.
iii) recall_score: Computes the recall of the model.
iv) f1_score: Computes the F1 score, which is the harmonic mean of precision and recall.
v) roc_auc_score: Computes the area under the Receiver Operating Characteristic (ROC) curve.


<img width="244" alt="Screenshot 2024-01-01 234010" src="https://github.com/Ishaswm/Stroke-Prediction/assets/122556303/51815a3b-0e83-4933-b305-6b23fa6cc5e3">

<img width="260" alt="Screenshot 2024-01-01 234020" src="https://github.com/Ishaswm/Stroke-Prediction/assets/122556303/f24e79ad-7988-4365-b131-353b119d8a12">

#

*Disclaimer: This model is based on Data Science Practices and nowhere is affiliated with any medical authority. Please consult with your doctor for consultations/medicines.*
