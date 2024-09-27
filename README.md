## Predicting Breast Cancer using different ML algorithms

The goal of this study is to make the best model to discriminate between benign and malignant breast cancer based on following 10
nuclei features:

1. Radius 

2. Texture

3. Perimeter

4. Area

5. Smoothness (local variation in radius)

6. Compactness

7. Concavity

8. Concave points

9. Symmetry

10. Fractal Dimension

The following ML algorithms were used in this project: Logistic Regression, KNN, Naive Bayes, Decision Tree, Random Forest, SVM

| ML metrics    | Logistic Regression | KNN  | Naive Bayes | Decision Tree | Random Forest | SVM |
| ------------- | ------------------  | -----| ------------| ------------- | ------------- | ----|
| recall=0      | 0.94  | Content Cell| 0.99 | 0.89        | 0.93          | 0.91          | 0.96|
| recall=1      | 0.89  | Content Cell| 0.91 | 0.89        | 0.94          | 0.94          | 0.89|
| accuracy      | 0.92  | Content Cell| 0.96 | 0.89        | 0.94          | 0.92          | 0.93|


Conclusion: The best performance to discriminate between benign and malignant tumor based on 10 nuclei features shows
the Decision Tree algorithm.
