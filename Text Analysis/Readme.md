# Project Title
Yelp Review Sentiment Analysis

## Project Overview
This project aims to perform sentiment analysis on Yelp reviews using natural language processing (NLP) techniques and machine learning models. The analysis classifies reviews into positive and negative sentiments. By leveraging algorithms like Complement Naive Bayes and Logistic Regression, this project helps to uncover customer sentiments, providing valuable insights for businesses to enhance customer satisfaction and improve their services.

## Dataset
- **Dataset Name:** Yelp Review Dataset
- **Source:** [Yelp Review Dataset](https://www.yelp.com/dataset)
- **File Format:** CSV
- **Encoding:** UTF-8

## Libraries Used
To run the code successfully, the following Python libraries are required:
- `pandas`: For data loading and manipulation.
- `numpy`: For handling numerical operations.
- `matplotlib` and `seaborn`: For data visualization.
- `nltk`: For natural language processing tasks.
- `wordcloud`: For visualizing word frequencies.
- `scikit-learn`: For machine learning model implementation and evaluation.
- `plotly`: For interactive visualizations.

## How to Run the Code
### Step 1: Clone or Download the Repository
- Download the project files or clone the repository to your local machine.

### Step 2: Place the Dataset
- Ensure that the Yelp review dataset is placed in the project folder and paths are updated in the code as necessary.

### Step 3: Execute the Python Script
Run the provided Python script to perform sentiment analysis. The script will:
- Load the dataset using pandas.
- Preprocess the data by cleaning the text and removing stop words.
- Visualize the data with histograms and word clouds.
- Vectorize the text data using CountVectorizer and TF-IDF Vectorizer.
- Train the Complement Naive Bayes and Logistic Regression models.
- Evaluate the models using accuracy scores, confusion matrices, and classification reports.

### Step 4: View the Results
- After execution, the script will display model accuracy, confusion matrices, and classification reports for both models. You can customize the parameters of the models to fine-tune the results according to your needs.

## How the Dataset Was Used
### 1. Data Preprocessing:
- The dataset was loaded and cleaned to remove unnecessary characters, URLs, and stop words.
- Sentiments were mapped from numerical values to textual labels ("positive" and "negative").
- The text data was tokenized and lemmatized for better representation.

### 2. Sentiment Analysis:
- Two machine learning models, Complement Naive Bayes and Logistic Regression, were trained on the preprocessed data.
- Each model's performance was evaluated based on accuracy, precision, recall, and F1 score.

### 3. Analysis Goal:
- The goal of this analysis is to accurately classify Yelp reviews into positive or negative sentiments, thereby providing insights into customer opinions and experiences that can aid businesses in making informed decisions regarding their services.

