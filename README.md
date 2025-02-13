# Unveiling-Audience-Insights-sentimetal-anlysis-

## Overview
With the exponential increase in textual data, particularly in the form of user-generated content, there has been a growing interest in applying machine learning (ML) and natural language processing (NLP) techniques to analyze this information. This project focuses on performing sentiment analysis on YouTube comments related to trending topics, leveraging various machine learning algorithms.

## Motivation
Despite the abundance of comments and feedback on various videos, extracting meaningful trends remains challenging due to issues such as low consistency and data quality. Our research aims to identify patterns, seasonality, and forecasting in sentiment analysis to offer insights into the impact of real-world events on public sentiment.

## Objectives
- Perform sentiment analysis on YouTube comments using a pre-existing annotated corpus of 1,500 citation sentences.
- Apply various data normalization techniques to clean and preprocess the dataset.
- Implement and evaluate six different machine learning algorithms:
  - Naïve Bayes (NB)
  - Logistic Regression (LR)
  - Decision Tree (DT)
  - Linear SVC
  - Random Forest (RF)
- Assess the performance of these models using key metrics such as F-score and Accuracy score.
- Enhance the reliability of sentiment analysis through advanced preprocessing techniques including:
  - Tokenization
  - Stopword removal
  - Stemming
  - Lemmatization
  - N-grams
  - Punctuation removal

## Data Collection
We utilize YouTube comments to measure user sentiment regarding video content. Sentiment analysis allows us to gain insights from large volumes of text data, making it a powerful tool for understanding user opinions. Our dataset comprises manually annotated comments categorized into three sentiment classes:
- **Positive**
- **Negative**
- **Neutral**

## Methodology
1. **Data Preprocessing**
   - Cleaning text data by removing noise (special characters, emojis, URLs, etc.)
   - Tokenization and stopword removal
   - Lemmatization and stemming for text normalization
   - Feature extraction using n-grams and vectorization techniques

2. **Model Training & Evaluation**
   - Train multiple machine learning classifiers
   - Evaluate models using accuracy, precision, recall, and F1-score
   - Compare model performances and identify the most effective approach

## Results & Findings
Our findings show that user sentiment trends correlate strongly with real-world events associated with specific keywords in comments. The integration of advanced NLP techniques improves classification accuracy, demonstrating how automated sentiment analysis can be an effective tool for tracking public opinion.

## Applications
This research highlights the potential of sentiment analysis in:
- Social media monitoring
- Business intelligence
- Market research
- Government policymaking

## How to Run the Project
### Prerequisites
- Python 3.x
- Jupyter Notebook or any Python IDE
- Required libraries: Pandas, Numpy, Scikit-learn, NLTK, Matplotlib, Seaborn

### Installation
Clone the repository:
```sh
 git clone https://github.com/your-username/YouTube-Sentiment-Analysis.git
 cd YouTube-Sentiment-Analysis
```
Install dependencies:
```sh
 pip install -r requirements.txt
```
Run the analysis:
```sh
 python sentiment_analysis.py
```

## Contributing
Contributions are welcome! Feel free to submit pull requests or open issues for discussions.

## Contact
For any inquiries, please reach out via [your-email@example.com , shrutithareja@gmail.com].

