# Bitcoin-Prediction-Model

** library used ** -- pandas, numpy, tqdm, mwclient, time, pipeline, yfinance, os, sklearn, XGBClassifier, ta

** Language and Skills used ** -- Python, Web Scraping, Sentiment Analysis, Random Forest Classifier

**Utilizing Web Scraping and Sentiment Analysis for Bitcoin Price Prediction**

### Introduction
In this project, we employ web scraping techniques to extract data from the Wikipedia page of Bitcoin. We then perform sentiment analysis on the collected textual data to gauge the sentiment surrounding Bitcoin. The objective is to predict Bitcoin prices for the following day using a Random Forest Classifier. We'll follow a detailed process including data extraction, cleaning, sentiment analysis, and model training.

### 1. Web Scraping
- **Wikipedia Page**: We scrape the Wikipedia page of Bitcoin using Python libraries like BeautifulSoup and requests.
- **Data Extraction**: Extract relevant textual information including historical events, news, and developments related to Bitcoin.

### 2. Sentiment Analysis
- **Text Preprocessing**: Clean the extracted text data by removing punctuation, stopwords, and special characters.
- **Sentiment Analysis**: Utilize Natural Language Processing (NLP) techniques and sentiment analysis tools like Vader or TextBlob to quantify the sentiment of the text data.
- **Sentiment Scoring**: Assign sentiment scores (positive, negative, neutral) to each textual entry.

### 3. Data Organization and Cleaning
- **Data Formatting**: Organize the extracted data into a structured format, such as a DataFrame.
- **Missing Data Handling**: Check for missing values and handle them appropriately, either by imputation or removal.
- **Feature Engineering**: Create additional features if necessary, such as sentiment scores or numerical representations of text data.

### 4. Model Preparation
- **Feature Selection**: Select relevant features for predicting Bitcoin prices, including sentiment scores and potentially other market indicators.
- **Data Splitting**: Split the dataset into training and testing sets.
- **Random Forest Classifier**: Implement the Random Forest Classifier, a popular ensemble learning technique, for predicting Bitcoin prices.
- **Model Training**: Train the Random Forest model on the training dataset.

### 5. Model Evaluation and Prediction
- **Model Evaluation**: Evaluate the trained model's performance using appropriate evaluation metrics such as accuracy, precision, recall, and F1-score.
- **Prediction**: Utilize the trained model to predict Bitcoin prices for the following day based on the sentiment analysis of the Wikipedia data.
- **Assessment of Results**: Assess the accuracy of the predictions and compare them with actual Bitcoin prices to gauge the model's effectiveness.

### Conclusion
In conclusion, this project demonstrates the integration of web scraping, sentiment analysis, and machine learning techniques for predicting Bitcoin prices. By leveraging textual data from Wikipedia and analyzing sentiment, we aim to provide insights into market sentiment surrounding Bitcoin and predict its future price movements. The Random Forest Classifier serves as a robust tool for this prediction task, with the potential for further refinement and optimization. Overall, this project showcases the application of data science methodologies in the cryptocurrency domain and contributes to understanding Bitcoin price dynamics.

## Future Scope 
In this project we can integrate indicators and some other methods to improve the accuracy of the predicton of this model.
