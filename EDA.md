# Exploring Heart Attack Risk Factors: A Data Analysis Perspective
---
Heart attacks, or myocardial infarctions, are a leading cause of death worldwide. Understanding the factors that contribute to heart attacks is crucial for prevention and early intervention. In this article, we will explore the relationship between various attributes related to heart attack and the presence of a heart attack using a dataset that includes information such as age, gender, chest pain type, resting blood pressure, serum cholesterol level, fasting blood sugar level, resting electrocardiographic results, maximum heart rate achieved, exercise-induced angina, ST depression induced by exercise relative to rest, slope of the peak exercise ST segment, number of major vessels colored by fluoroscopy, thalassemia, and the presence of a heart attack.

### Dataset Overview
Each row in the dataset represents an individual with various attributes related to heart attack, and the last column "target" indicates whether the person experienced a heart attack (1 for yes and 0 for no).

### Correlation Analysis
We conducted a correlation analysis to understand the relationships between different features in the heart attack dataset. Here are some key observations:

![alt text](https://github.com/pratibharoy/Pratibha-Dipika/blob/main/WhatsApp%20Image%202024-03-10%20at%2012.53.09.jpeg?raw=true)

#### Positive Correlations:

Chest Pain Type (cp) has a positive correlation with Maximum Heart Rate Achieved (thalach) and Slope.
Maximum Heart Rate Achieved (thalach) has a positive correlation with Slope.

#### Negative Correlations:

Age has a negative correlation with Maximum Heart Rate Achieved (thalach).
Gender (sex) has a negative correlation with the presence of a heart attack (target).

#### Strong Correlations:

Chest Pain Type (cp) has a moderate positive correlation (0.42) with the presence of a heart attack (target).
Maximum Heart Rate Achieved (thalach) also has a moderate positive correlation (0.40) with the presence of a heart attack (target).

---
### Distribution Analysis
We also analyzed the distribution of certain features in the dataset. Here are some key findings:

![alt text](https://github.com/pratibharoy/Pratibha-Dipika/blob/main/Screenshot%202024-03-10%20125717.png?raw=true)


1. The center of distribution for Serum Cholesterol Level (chol) and ST Depression Induced by Exercise Relative to Rest (oldpeak) is positively skewed.
2. The distribution of Resting Blood Pressure (trestbps) is approximately symmetric.
3. The center of distribution for Maximum Heart Rate Achieved (thalach) and Age is negatively skewed.
Model Evaluation
We trained a machine learning model to predict the presence of a heart attack based on the dataset. Here are the evaluation metrics:

---
### Confusion Matrix:

![alt text](https://github.com/pratibharoy/Pratibha-Dipika/blob/main/Screenshot%202024-03-10%20141841.png?raw=true)
![alt text](https://github.com/pratibharoy/Pratibha-Dipika/blob/main/Screenshot%202024-03-10%20141934.png?raw=true)


True Positives (TP): 103 cases correctly predicted positive outcomes.
True Negatives (TN): 102 cases correctly predicted negative outcomes.
False Positives (FP): 0 cases incorrectly predicted positive outcomes.
False Negatives (FN): 0 cases incorrectly predicted negative outcomes.
Precision: 1.00 for both classes, indicating no false positives.

Recall: 1.00 for both classes, indicating no false negatives.

F1-Score: 1.00, indicating a balanced performance in terms of precision and recall.

Accuracy: Approximately 99% accuracy in predicting the presence of a heart attack.

In conclusion, this analysis provides valuable insights into the factors that contribute to heart attacks. Features such as Chest Pain Type (cp), Maximum Heart Rate Achieved (thalach), and ST Depression Induced by Exercise Relative to Rest (oldpeak) are important predictors of heart attack risk. Understanding these factors can help healthcare professionals identify individuals at higher risk and implement preventive measures. Further research and analysis are needed to validate these findings and improve the prediction of heart attacks.

---

# Article Reviews
Heart diseases encompass a wide range of diseases that affect the heart and pose a substantial
global health concern. Cardiovascular illnesses are the leading cause of death worldwide, killing
17.9 million people each year. Heart disease development is influenced by a variety of risk
factors, including excessive cholesterol, obesity, increased triglycerides, and hypertension.
Recognizable symptoms, as described by groups such as the American Heart Association,
include irregular heartbeats, swollen legs, rapid weight gain, and sleep disturbances. Early
diagnosis is difficult due to symptom overlap with other disorders, especially in the elderly,
which can lead to death. Advances in research, combined with the increased availability of
patient records, have created opportunities for using machine learning and artificial intelligence
to improve diagnosis accuracy and forecast outcomes in cardiac disease.

#### Understanding Risk Factors:
Heart illnesses impact people of all ages, genders, and backgrounds. Several lifestyle and health
variables influence their growth. High cholesterol, obesity, high triglycerides, and hypertension
are some of the major risk factors that might harm heart health. Sedentary lifestyles, poor dietary
choices, and genetic predispositions compound these risks, emphasizing the importance of early
detection and intervention.

#### Recognizing Symptoms:
Identifying symptoms of heart disease can be difficult due to their various nature, which might
be confused for other health concerns. The American Heart Association identifies significant
signs such as irregular heartbeat, swelling legs, fast weight gain, and sleep difficulties. When
these symptoms are detected together, they indicate the necessity for a full medical investigation.
The difficulty lies in separating these manifestations from those caused by the natural aging
process or other unrelated disorders.

#### Diagnostic Challenges:
Effective management of cardiac disease requires accurate and fast diagnosis. However, the
overlapping symptoms make this a difficult process. Misdiagnosis provides a considerable
danger to patient outcomes. As medical knowledge and technology advance, researchers and
healthcare professionals are investigating novel techniques to improve diagnosis accuracy.

Heart illnesses remain a major worldwide health concern, necessitating ongoing study,
awareness, and novel solutions. The complex interaction of risk factors, combined with the
enigmatic character of symptoms, necessitates a comprehensive approach to prevention and
diagnosis. The use of machine learning and artificial intelligence into cardiovascular healthcare
holds the possibility of more accurate and timely therapies, bringing hope for better outcomes
and a healthier future. As research and technology develop, the continued commitment to
understanding the complexity of cardiac disease remains critical to global well-being.

[Conclusion](https://pratibharoy.github.io/Heart-disease/Conclusion)

