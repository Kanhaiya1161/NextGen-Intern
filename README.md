This repository contains Python implementations for analyzing multiple datasets, focusing on customer behavior using Sentiment Analysis, Decision Tree, and K-Means Clustering. Each technique is applied to different datasets to provide insights into customer segmentation and behavior patterns.

Datasets
Mall Customer Dataset
This dataset contains information about customers who visit a mall. It includes attributes such as:
Customer ID
Age
Annual Income
Spending Score
Review/Feedback (for Sentiment Analysis)
Additional Dataset 1 (Decision Tree)
This dataset is used for Decision Tree Classification to predict customer categories based on attributes like demographics or spending behavior.

Additional Dataset 2 (K-Means Clustering)
This dataset is used for K-Means Clustering to segment customers into distinct groups based on similar characteristics.

Methods
1. Sentiment Analysis (Mall Customer Dataset)
Sentiment Analysis is performed on customer reviews/feedback to classify their sentiments into positive, neutral, or negative categories. This provides valuable insights into customer satisfaction and feedback trends.

Input: Customer review/feedback text.
Output: Sentiment (Positive/Negative/Neutral).
Algorithm: Natural Language Processing (NLP) using libraries like NLTK or TextBlob.
2. Decision Tree Classification (Additional Dataset 1)
The Decision Tree algorithm is applied to classify customers based on their demographic and behavioral features, such as age, income, and spending score. It helps predict customer categories like high spender, low spender, etc.

Input: Various customer attributes (e.g., age, income, spending score).
Output: Predicted customer category.
Algorithm: Scikit-learn's Decision Tree Classifier.
3. K-Means Clustering (Additional Dataset 2)
K-Means Clustering is used to group customers into distinct clusters based on similar characteristics. This segmentation helps in targeting specific customer groups with personalized offers or services.

Input: Customer attributes (e.g., age, income, spending score).
Output: Customer clusters.
Algorithm: Scikit-learn's KMeans Clustering.
Prerequisites
Make sure you have the following libraries installed:

pandas
numpy
matplotlib
scikit-learn
nltk or textblob (for sentiment analysis)
seaborn

License
This project is licensed under the MIT License - see the LICENSE file for details.
