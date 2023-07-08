# Classification-Model-Analysis

An ananlysis on the following models has been carried out:

| Models |
| ------------- |
| Decision Tree |
| K Nearest Neighbors |
| Naive Bayes Model |
| Logistic Regression |

**Breast Tissue** Dataset is used for training these models.

# Dataset 

Breast Tissue Dataset consists of 106 rows and 10 columns

| Sno | Column | Non-Null Count | Dtype |
| --- | ------ | -------------- | ----- | 
| 1 | Class  | 106 non-null |  object | 
| 2 | I0     | 106 non-null |  float64 |
| 3 | PA500  | 106 non-null |  float64 |
| 4 | HFS    | 106 non-null |  float64 |
| 5 | DA     | 106 non-null |  float64 |
| 6 | Area   | 106 non-null |  float64 |
| 7 | A/DA   | 106 non-null |  float64 |
| 8 | Max IP | 106 non-null |  float64 |
| 9 | DR     | 106 non-null |  float64 |
| 10 | P     | 106 non-null |  float64 |

The tissues are classified into 6 types namely:

 - Carcinoma (car)
 - Fibro-adenoma (fad)
 - Mastopathy (mas)
 - Glandular (gla)
 - Connective (con)
 - Adipose (adi)


# Outcome

Following outcomes were noted from the analysis:
| Model | Accuracy Score |
| ----- | -------------- |
| Decision Tree | 0.545 |
| KNN |0.590 |
| Naive Bayes | 0.590 |
| Logistic Regression (Multinomial) | 0.636 |
| Logistic Regression (One vs Rest) | 0.727 |
