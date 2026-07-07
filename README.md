# Multi-Class Text Classification using Machine Learning and Deep Learning

A comprehensive Natural Language Processing (NLP) project that evaluates the effectiveness of traditional Machine Learning and Deep Learning approaches for multi-class text classification. This project presents a comparative study of four text representation techniques across ten classification models using a large-scale Question Answer Classification dataset.

The project includes an end-to-end NLP pipeline covering data preprocessing, exploratory data analysis (EDA), feature engineering, word embeddings, model development, hyperparameter tuning, performance evaluation, and comparative analysis. A total of **22 experiments** were conducted to identify the most effective combination of word representation and classification model.

## Project Highlights

- Large-scale multi-class text classification on a dataset containing **280,000+** training samples across **10 balanced categories**
- Comprehensive Exploratory Data Analysis (EDA)
- Advanced text preprocessing using NLTK
- Comparison of four text representation techniques:
  - Bag of Words (BoW)
  - TF-IDF
  - GloVe Embeddings
  - Skip-gram Word2Vec
- Implementation of three traditional Machine Learning models:
  - Logistic Regression
  - Random Forest
  - Naive Bayes
- Implementation of seven Neural Network architectures:
  - Deep Neural Network (DNN)
  - SimpleRNN
  - Bidirectional SimpleRNN
  - GRU
  - Bidirectional GRU
  - LSTM
  - Bidirectional LSTM
- Hyperparameter optimization across **22 experiments**
- Model evaluation using Accuracy, Macro F1-score, Weighted F1-score, Precision, Recall, and Confusion Matrix
- Comparative performance analysis between classical Machine Learning and Deep Learning models

## Dataset

- **Dataset:** Question Answer Classification Dataset
- **Training Samples:** 280,003
- **Classes:** 10
- **Domain:** Multi-class Question Classification

## Best Results

| Model | Accuracy |
|------|----------:|
| TF-IDF + Naive Bayes | **74.46%** |
| Skip-gram + BiGRU | **72.44%** |

The experimental results demonstrate that **TF-IDF combined with Naive Bayes** achieved the highest overall classification performance, while **Skip-gram with Bidirectional GRU** delivered the strongest results among all deep learning models.

## Technologies Used

- Python
- Jupyter Notebook
- TensorFlow / Keras
- Scikit-learn
- NLTK
- Gensim
- NumPy
- Pandas
- Matplotlib
- Seaborn

## Repository Structure

```
.
├── README.md
├── LICENSE
├── requirements.txt
├── .gitignore
└── Text_Classification.ipynb
```

## Future Improvements

- Fine-tune transformer-based language models (BERT, RoBERTa, DistilBERT)
- Implement attention-based sequence models
- Explore ensemble learning techniques
- Perform automated hyperparameter optimization
- Deploy the trained model as a REST API or web application

## Author

**Masrur Hoque**

Computer Science and Engineering
```
