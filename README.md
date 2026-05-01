# comp6420-nlp-a2
This project develops a duplicate question detection system using the Quora Question Pairs dataset. It applies NLP preprocessing, classical machine learning (Naïve Bayes), deep learning (Siamese LSTM), and Transformer-based models to classify semantic similarity between question pairs, with a focus on model comparison and error analysis.

🧠 Project Overview

This project implements a duplicate question classification system using the Quora Question Pairs (QQP) dataset. It explores multiple approaches—from basic NLP preprocessing to advanced deep learning models—to determine whether two questions have the same semantic meaning.

📊 Dataset
Quora Question Pairs (QQP)
Over 400,000 labelled question pairs
Task: classify whether two questions are duplicates (1) or not (0)

🚀 Methods

The project is structured into five main stages:

Text Processing
Tokenization and POS tagging (NLTK)
Extraction of the most common nouns
N-gram Analysis
Bigram extraction (stemmed and non-stemmed)
Frequency normalization
Naïve Bayes Model
Bag-of-Words representation
Evaluation: accuracy, precision, recall
Siamese Neural Network
Dual LSTM encoders with shared weights
Cosine similarity for classification
Evaluation: accuracy, F1-score
Transformer Model
Fine-tuned pre-trained model (e.g., BERT)
Evaluation: accuracy, precision, recall, F1-score
Includes error analysis

📈 Results & Analysis
Compared performance across all models
Analysed error types (false positives vs false negatives)
Evaluated how well each model captures semantic meaning

🛠️ Technologies
Python
NLTK
NumPy
Scikit-learn
PyTorch / TensorFlow
Hugging Face Transformers

▶️ Running the Project
Install dependencies
Open the Jupyter Notebook
Run all cells to reproduce results

📌 Notes
Uses a reduced dataset subset for efficiency
Focus on both implementation and analytical insights
