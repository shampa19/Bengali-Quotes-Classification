Bangla Quotes Classification – Comparative Analysis

This project focuses on text classification of Bangla quotes into multiple categories using both classical machine learning algorithms and deep learning models. The goal is to evaluate how traditional approaches compare with advanced neural architectures for multiclass text classification in the Bangla language.

📌 Overview

Dataset: Bangla Quotes Dataset (preprocessed and cleaned for classification tasks).

Algorithms Used:

Multinomial Naive Bayes (MNB)

Logistic Regression (LR)

Long Short-Term Memory (LSTM)

Bidirectional LSTM (Bi-LSTM)

Objective: Compare accuracy and performance metrics across algorithms to determine the best-suited model for Bangla text classification.

⚙️ Methodology

Preprocessing

Tokenization and stopword removal for Bangla text.

Text-to-sequence conversion with padding for deep learning models.

Models Implemented

MNB & LR: Trained on TF-IDF features.

LSTM & Bi-LSTM: Trained on word embeddings with sequence input.

Evaluation Metrics

Precision

Recall

F1-Score

Accuracy

📊 Results

Table II: Accuracy table for multiclass classification

Algorithm	Precision	Recall	F1-Score	Accuracy
Multinomial Naive Bayes (MNB)	0.5860	0.6264	0.5900	62.65%
Logistic Regression (LR)	0.6317	0.6706	0.6358	67.06%
Long Short-Term Memory (LSTM)	0.9212	0.9283	0.9212	92.84%
Bidirectional LSTM (Bi-LSTM)	0.9493	0.9462	0.9434	94.63%

📌 Observation:

Traditional ML algorithms (MNB, LR) perform moderately.

Deep learning models (LSTM, Bi-LSTM) show significant improvement, with Bi-LSTM outperforming all in every metric.

🚀 Conclusion

Bi-LSTM is the most effective approach for Bangla Quotes classification, achieving 94.63% accuracy.

This highlights the advantage of deep contextual representation for Bangla text.

Future work can focus on transformer-based models (e.g., BERT, mBERT, BanglaBERT) for further improvements.

📂 Files in Repository

Bangla_Quotes_Classification_With_Logistic_Regression_&_Multinomial_Naive_Bayes.ipynb → Classical ML models

Bangla_Quotes_Classification_With_LSTM.ipynb → Deep learning LSTM

Bangla_Quotes_Classification_With_BiLSTM.ipynb → Bidirectional LSTM

🔧 Requirements

Install dependencies with:

pip install -r requirements.txt
