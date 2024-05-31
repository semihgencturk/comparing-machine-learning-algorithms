# Comparing Machine Learning Algorithms on Balanced and Imbalanced Datasets

- My thesis is avaliable on my [google drive](https://drive.google.com/file/d/1ISgFsQ0uER3jV5wRcYVUR5kFgzngdHtU/view?usp=sharing).

## ABSTRACT

This study investigates the performance of three machine learning algorithms—Logistic
Regression, K-Nearest Neighbors (KNN), and Random Forest—on imbalanced and
balanced datasets. Using the Churn Modelling and HR Employee Analytics datasets from
Kaggle, the algorithms were initially evaluated on their imbalanced versions. Then,
SMOTE was applied to balance the datasets, and the algorithms were re-evaluated.

The Random Forest algorithm consistently outperformed the others in both ROC and PR
curve metrics. After balancing the datasets with SMOTE, the performance of all
algorithms improved. However, Random Forest still demonstrated the best performance,
showing its robustness and adaptability to balanced data. Additionally, balancing the data
was found to be significantly more important for Logistic Regression since the incresing
of algorithm performance are very high while there is no big changes observed for others.
For instance, in the Churn Modelling dataset, Random Forest's ROC score improved from
0.94 to 0.95 and in the HR Employee Analytics dataset from 0.99 to 0.995, while the
improvements for Logistic Regression were more substantial, increasing from 0.77 to
0.88 and from 0.81 to 0.87.

Overall, this study emphasizes that Random Forest provides better performance for both
balanced and imbalanced datasets. Moreover, while Random Forest and K-Nearest
Neighbors (KNN) algorithms did not show significant performance changes with data
balancing, the process was beneficial for Logistic Regression. Therefore, balancing with
SMOTE enhances algorithm performance, providing valuable insights for future
predictive modeling tasks involving imbalanced data.
