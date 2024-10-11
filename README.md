# Sentiment Analysis Project

This project implements a **sentiment analysis model** using the **Naive Bayes** algorithm on customer reviews. The aim is to classify reviews as positive or negative based on the textual content.

## Key Features:
- **Data Preprocessing**: 
  - Cleaning and transforming text data using techniques such as:
    - Removal of special characters and stopwords.
    - Stemming to reduce words to their base forms.
- **Bag of Words (BoW)**: 
  - Utilizes `CountVectorizer` to convert text data into numerical format, enabling machine learning algorithms to process the text.
- **Model Training**:
  - Employs the Gaussian Naive Bayes algorithm for classification tasks.
  - Splits the dataset into training and testing sets to evaluate model performance.
- **Performance Evaluation**: 
  - Uses confusion matrix and accuracy score to assess the model's effectiveness.

## Technologies Used:
- Python
- scikit-learn
- NLTK
- Pickle/Joblib for model serialization

## Installation and Usage:
1. Clone the repository: 
   ```bash
   git clone https://github.com/asma1104hchr/Sentiment-Analysis-Project-using-Machine-Learning-NLP-Review-Classification.git
