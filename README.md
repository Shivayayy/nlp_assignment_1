
# Sentiment Polarity Classifier

A Natural Language Processing project to classify movie review sentiments using machine learning techniques.

## Overview

This project implements a binary sentiment classifier to determine whether a movie review expresses a positive or negative sentiment. We compare the performance of Support Vector Machine (SVM), Naive Bayes, and Logistic Regression models.

## Dataset

- 10,662 movie review sentences (5,331 positive, 5,331 negative)
- Source: [Cornell Movie Review Dataset](https://www.cs.cornell.edu/people/pabo/movie-review-data/rt-polaritydata.tar.gz)

## Key Features

- Text preprocessing pipeline (tokenization, stop word removal, TF-IDF vectorization)
- Implementation of three ML models: SVM, Naive Bayes, Logistic Regression
- Model performance comparison and analysis

## Results

Naive Bayes emerged as the best-performing model:
- Highest Recall: 0.93
- Best F1-Score: 0.80

## Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/Shivayayy/nlp_assignment_1.git
   cd nlp_assn1
   ```

2. Set up a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Run the classifier:
   ```
   python sentiment_analysis.py
   ```

## Additional Resources

- [SVM Implementation (Colab)](link-to-svm-notebook)
- [Logistic Regression Implementation (Colab)](link-to-logistic-regression-notebook)
- [Naive Bayes Implementation (Colab)](link-to-naive-bayes-notebook)

## Contributors

- Shivam Kumar Dwivedi

## License

This project is open-source and available under the MIT License.
