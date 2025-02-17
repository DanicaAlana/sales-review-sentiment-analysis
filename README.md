# **Sentiment Analysis of Amazon Sales Review Dataset Using Multinomial Naive Bayes Method**

**Description:**
This project is a sentiment analysis project using a machine learning model. It analyzes Amazon product reviews to determine whether the sentiment expressed is positive, negative, or neutral. The project uses a dataset of Amazon product reviews (amazon.csv) and applies a Multinomial Naive Bayes model for classification.

**Goals:**

1. Building a sentiment analysis model: To develop a model that can accurately classify the sentiment of Amazon product reviews.
2. Preprocessing and analyzing data: To clean and prepare the data for modeling, including handling missing values, removing duplicates, and converting ratings to sentiment labels.
3. Extracting features: To use TF-IDF (Term Frequency-Inverse Document Frequency) to convert text reviews into numerical representations for the model.
4. Evaluating model performance: To assess the accuracy and performance of the trained model using metrics such as accuracy and classification report.

**Insights:**
1. Data preprocessing is crucial: Cleaning and preparing the data significantly impacts the model's performance. Steps like removing stop words, handling missing values, and converting ratings to sentiment categories are essential.
2. TF-IDF effectively captures text features: Using TF-IDF to vectorize the text data allows the model to learn from the important words and phrases in the reviews.
3. Multinomial Naive Bayes is a suitable model: This model performs well for text classification tasks and provides decent accuracy in sentiment analysis.

**Conclusion**

The project successfully built a sentiment analysis model for Amazon product reviews using a Multinomial Naive Bayes classifier. The model achieved a certain level of accuracy in classifying reviews as positive, negative, or neutral. The project highlights the importance of data preprocessing and feature extraction in achieving accurate sentiment analysis results. Future improvements could involve exploring other models or using more advanced techniques for feature engineering. To check the accuracy of the model, refer to the output of the cell that includes print(f'Akurasi: {accuracy:.2f}%') and print(classification_report(y_test, y_pred)).

If you have any questions, suggestions or feedbacks, please do not hesitate to reach me out through Email or LinkedIn: sjurjahady29@gmail.com or https://www.linkedin.com/in/danicaas
