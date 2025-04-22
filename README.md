# Sentiment-analysis

*COMPANY*- CODTECH IT SOLUTION

*NAME*- ASESHTA GOYAL

*INTERN ID*- CT04DA481

*DOMAIN*- DATA ANALYTICS

*DURATION*- 4 WEEKS

*MENTOR*- NEELA SANTOSH

## Project Description: Sentiment Analysis on Social Media Posts

This project focuses on applying Natural Language Processing (NLP) techniques to perform sentiment analysis on a dataset of social media posts. Sentiment analysis, also known as opinion mining, is a technique used in data science and machine learning to identify and extract subjective information from text. It helps determine whether the sentiment behind a particular text is positive, negative, or neutral.

## Tools and Technologies Used

For this task, we utilized a combination of Python libraries, data science tools, and NLP techniques, specifically:

- Python: The primary programming language used for all analysis and modelling tasks.

- Pandas: Used for data loading, cleaning, manipulation, and exploration.

- NLTK (Natural Language Toolkit): Employed for text preprocessing tasks such as tokenization, stopword removal, and basic NLP cleaning.

- Scikit-Learn:

  - TfidfVectorizer: Used to convert text data into numerical format (vectorization) for machine learning models.
 
  - LogisticRegression: Selected as the classification model for sentiment prediction.
 
  - train_test_split, classification_report, and confusion_matrix: Used to train the model, test it, and evaluate performance.

- Matplotlib and Seaborn: Libraries for data visualization and insight extraction.

All development and execution were done using Google Colab, a cloud based Jupyter notebook platform provided by Google. Colab provides free access to computing resources, Python environments, and GPU acceleration, making it a suitable choice for data science and machine learning tasks, especially during internships or projects with limited local resources.

## Task Execution Overview

1. Dataset Preparation:

   - We started with a CSV file named social_media_posts.csv containing basic post metadata (e.g., user ID, post type, likes, timestamp, etc.).
  
   - As the dataset did not contain post text or sentiment, we simulated a post_text column with various user like messages and generated corresponding sentiment labels (positive, neutral, or negative) using a rule based approach.

2. Text Preprocessing:

   - The post_text was preprocessed by converting to lowercase, removing punctuation, tokenizing the words, and removing common English stopwords.
  
   - The cleaned text was stored in a new column clean_text.

3. Feature Extraction and Vectorization:

   - We used TfidfVectorizer to transform the cleaned text into numerical features that could be understood by machine learning algorithms.

4. Model Building and Evaluation:

   - A Logistic Regression model was trained on the transformed data to predict sentiment.
  
   - We evaluated the model using a classification report and confusion matrix.
  
   - Additionally, we visualized the most influential words associated with positive and negative sentiments using bar charts.
  
5. Insights and Visualization:

   - From the trained model, we extracted and visualized the top positive and negative keywords contributing to sentiment classification. This step gives practical interpretability to the model's behavior.

## Real World Applications

The techniques demonstrated in this project have significant real world applications, including:

- Brand Monitoring: Companies can analyze customer feedback or mentions on social media to monitor brand perception in real time.

- Customer Service Automation: Sentiment analysis can be used in chatbot systems to detect frustrated or satisfied users and tailor responses accordingly.

- Political and Social Analysis: Governments and researchers can analyze public opinion on policies or social events using real time sentiment tracking.

- Product Feedback Analysis: E-commerce platforms use sentiment analysis to automatically classify product reviews as positive, negative, or neutral.

- Stock Market Prediction: Financial institutions use sentiment from financial news and social media to inform trading strategies.

## Conclusion

This project served as a hands on exercise in text data handling, preprocessing, feature engineering, model building, and performance evaluation using real world techniques. By leveraging Python and cloud platforms like Google Colab, we were able to simulate a real world sentiment analysis pipeline from scratch. This experience contributes significantly to understanding how data science and NLP are applied in pratical scenarios and helps build foundational skills for a career in data analysis or machine learning.
