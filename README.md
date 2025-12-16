# Sentiment Analysis using Naive Bayes

This project classifies text reviews as positive or negative using Natural Language Processing (NLP) techniques and a Naive Bayes classifier.

## Project Objective
The goal is to analyze customer reviews and determine their sentiment, which helps businesses understand customer feedback and improve products or services.

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab / Jupyter Notebook

## Dataset
- Sample dataset with text reviews and corresponding sentiment labels.
- Columns:
  - `Review`: Customer review text
  - `Sentiment`: Label indicating Positive or Negative sentiment

## Workflow
1. **Data Loading:** Load dataset into a Pandas DataFrame.  
2. **Text Preprocessing:** Convert text to lowercase (optional preprocessing).  
3. **Feature Extraction:** Convert text into numeric features using `CountVectorizer`.  
4. **Train-Test Split:** Split data into training and testing sets.  
5. **Model Training:** Train a Naive Bayes classifier.  
6. **Evaluation:** Predict sentiments and calculate accuracy; visualize results with a confusion matrix.

## Results
- The model achieved an accuracy of approximately 0.66 with a small sample dataset.  
- Successfully classified reviews into positive and negative sentiments.  
- Visualization of results helps understand model performance.

## Conclusion
This project demonstrates a complete NLP pipeline for sentiment analysis using Naive Bayes. It highlights preprocessing, feature extraction, model training, and evaluation steps for text data. With a larger dataset, the model accuracy can be further improved.

## How to Run
1. Upload your dataset (or use the provided sample dataset) to Google Colab or local environment.  
2. Run the notebook `sentiment_analysis_nlp.ipynb`.  
3. Evaluate results and visualize with confusion matrix.
