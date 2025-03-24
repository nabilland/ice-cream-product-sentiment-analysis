<div align="center">

# A Sentiment Analysis on Skewed Product Reviews: Ben & Jerry's Ice Cream  

**Nabilla Nurulita Dewi, Sekar Gesti Amalia Utami, Shalsabila Aura Adiar, Hasan Dwi Cahyono**  
Faculty of Information Technology and Data Science, Universitas Sebelas Maret, Surakarta, Indonesia  

</div>

---

## Overview

Sentiment analysis of product reviews offers valuable insights into consumer perspectives, which can inform product development and marketing strategies. Given the growing importance of user-generated content like product reviews, this study explores sentiment classification in online reviews of Ben & Jerry's ice cream. We designed and evaluated three machine learning algorithms for sentiment classification: Naïve Bayes (NB), Logistic Regression (LR), and Support Vector Machine (SVM).

The dataset exhibits a significant class imbalance, with substantially more positive than negative reviews. To address this issue, we employed two oversampling techniques: the Synthetic Minority Oversampling Technique (SMOTE) and the Adaptive Synthetic Sampling Approach (ADASYN). Among the models tested, the combination of SVM with ADASYN demonstrated the highest accuracy, suggesting strong potential for robust and efficient performance in imbalanced binary sentiment classification tasks.

(A version of the article with track changes enabled to accommodate the latest revisions)

---

## Dataset

- Source: Online reviews of Ben & Jerry's ice cream.
- Sentiment labels: Binary (Positive and Negative).
- The dataset is highly imbalanced, with a dominant proportion of positive reviews.
 
Detailed preprocessing steps and class distribution visualization are available in the provided notebook. 

---

## Methodology

We implemented and compared the following supervised learning algorithms:

- Naïve Bayes (NB)  
- Logistic Regression (LR)  
- Support Vector Machine (SVM)

To mitigate the class imbalance issue, we applied the following oversampling techniques:

- SMOTE (Synthetic Minority Oversampling Technique)  
- ADASYN (Adaptive Synthetic Sampling Approach)

Model performance was evaluated before and after oversampling to assess the impact of data balancing on classification accuracy.

---

## Results Summary

| Model                  | Original Accuracy | Accuracy w/ ADASYN |
|------------------------|-------------------|---------------------|
| Naïve Bayes            | 91.90%            | 92.04%              |
| Logistic Regression    | 93.77%            | 94.96%              |
| Support Vector Machine | **95.09%**        | **95.23%**          |

- The application of ADASYN generally improved classification performance across all models.
- The combination of Support Vector Machine and ADASYN yielded the highest accuracy, demonstrating its effectiveness for binary sentiment classification with imbalanced data.

Additionally, a detailed comparison of algorithm performance across the top and bottom five (5) Ben & Jerry’s ice cream products is included. This comparison covers the results from the original dataset and those processed using SMOTE and ADASYN techniques. Results are also presented in the accompanying Jupyter notebook. 
