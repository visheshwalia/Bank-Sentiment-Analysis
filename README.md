**GitHub Repository: Bank Reviews Sentiment Analysis and Rating Prediction**

**Description:**
This repository houses Python code for comprehensive analysis of bank reviews and complaints. The code covers various stages, from data preprocessing to advanced natural language processing techniques. It performs sentiment analysis to categorize customer feedback as positive, negative, or neutral. Additionally, it utilizes topic modeling to extract key themes from the reviews.

**Key Features:**

- **Sentiment Analysis:** The code utilizes TextBlob to perform sentiment analysis on the reviews, allowing for the automatic categorization of sentiment as positive, negative, or neutral.

- **Topic Modeling:** Latent Dirichlet Allocation (LDA) is employed to uncover latent topics within the reviews and assign words to these topics.

- **Supervised Learning:** Beyond sentiment analysis and topic modeling, the code employs supervised learning techniques. It uses Support Vector Machine (SVM) with a linear kernel to predict star ratings based on the textual content of the reviews.

- **Data Transformation:** Bag of words (BoW) and Term Frequency-Inverse Document Frequency (TF-IDF) representations are applied to transform the text data for machine learning.

- **Model Evaluation:** The performance of the SVM model in predicting star ratings is assessed through metrics such as accuracy, confusion matrix, and ROC AUC score.

This repository serves as a comprehensive example of text data preprocessing, sentiment analysis, topic modeling, and supervised learning techniques applied to real-world bank reviews and complaints data. It demonstrates the holistic analysis of customer feedback, including sentiment categorization and star rating prediction.
