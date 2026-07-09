Glucose and Insulin show a strong positive correlation. This makes sense, 
as high glucose levels typically correlate with higher insulin levels, especially in diabetic patients.

Outcome (indicating whether a person has diabetes or not) seems to have some correlations with Age, BMI, and Glucose.
These factors are well-known to influence the likelihood of having diabetes, which aligns with what we'd expect from medical data.

BMI and Age also seem somewhat correlated, suggesting that older individuals may have higher BMI on average,
which is consistent with general health trends.

DiabetesPedigreeFunction shows lower correlations with other variables, 
indicating that it's not strongly correlated with any other factors but may still hold some predictive power for diabetes status.



Outcome 0 (No diabetes): This group has a significantly larger number of individuals,
as shown by the red bar at the top. It suggests that more individuals in the dataset do not have diabetes.

Outcome 1 (Diabetes): This group is much smaller, indicating fewer people in the dataset have diabetes.

This imbalance in the dataset is common in health-related datasets, 
Such class imbalances can influence model performance, especially when building predictive models

 


The dataset contains 768 rows, which can be considered medium-sized. For model development, 80% of the data was used for training. 
The dataset is imbalanced, with 500 non-diabetic cases and 268 diabetic cases.

When applying the K-Nearest Neighbors (KNN) algorithm, the model achieved an accuracy of 69% at k = 5. As we increased the value of k,
the model’s performance improved. This indicates that higher values of k help the model generalize better, 
likely due to the smoothing effect that reduces the influence of noise in an imbalanced dataset. Therefore,
it is possible to achieve better accuracy with the KNN model by selecting an appropriate larger value of k.

https://colab.research.google.com/github/R-WEB-netizen/tutedude.4/blob/main/K-nn.ipynb  (google colab link)
