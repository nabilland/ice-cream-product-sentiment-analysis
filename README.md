# A Sentiment Analysis on Skewed Product Reviews: Ben & Jerry's Ice Cream

This repository contains the source code for the sentiment analysis of Ben & Jerry’s ice cream product reviews. The goal is to understand consumer opinions and improve product offerings by analyzing sentiment from user-generated content.

## Dataset
The dataset used in this study is sourced from [Kaggle](https://www.kaggle.com/datasets/tysonpo/ice-cream-dataset) and includes various Ben & Jerry's ice cream products and their reviews.

## Methods
- Naive Bayes
- Logistic Regression
- Support Vector Machine (SVM)
  
Due to the imbalance in the dataset, the Synthetic Minority Over-sampling Technique (SMOTE) is applied to balance the data.

## Previous Work
Previous research on sentiment analysis of product reviews primarily utilized Naive Bayes and Logistic Regression algorithms. These methods have been effective in classifying sentiment as positive or negative.

## Results
The inclusion of SVM in our study provided a comparison of different classification methods. Here are the results:

- Before data balancing, the models achieved the following accuracies:
   - Naive Bayes: 87.14%
   - Logistic Regression: 93.77%
   - Support Vector Machine (SVM): 95.23%
  
- After data balancing using SMOTE, the accuracies improved to:
  - Naive Bayes: 92.57%
  - Logistic Regression: 94.50%
  - Support Vector Machine (SVM): 95.36%

The results indicate that SVM consistently outperformed Naive Bayes and Logistic Regression in both balanced and imbalanced data.

## Acknowledgements
The authors of this work would like to thank the Informatics Undergraduate Study Program, Faculty of Information Technology and Data Science, Universitas Sebelas Maret for providing the necessary facilities and resources.

## Contributing
Contributions are welcome! Please create a pull request or open an issue to discuss any changes.

## Contributors
<a href="https://github.com/nabilland/ice-cream-product-sentiment-analysis/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=nabilland/ice-cream-product-sentiment-analysis" />
</a>

Made with [contrib.rocks](https://contrib.rocks).
