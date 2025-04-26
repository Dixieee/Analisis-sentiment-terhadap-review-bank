
# Sentiment Analysis of Bank Reviews 🏦

This project involves sentiment analysis of customer reviews for Indonesian banks. The objective is to classify the reviews into three sentiment categories: **Positive**, **Neutral**, and **Negative**. Machine learning algorithms are employed to perform this classification. 🤖

## Project Overview 🌟

The project uses various preprocessing techniques, including tokenization, normalization, stopword removal, and stemming, to clean the review data. Several machine learning classifiers, including K-Nearest Neighbors (KNN), Random Forest, Naive Bayes, and Support Vector Machines (SVM), are used to train the model and classify the sentiment of the reviews.

## Features 🚀

- **Text Preprocessing**: Tokenization, normalization, stopword removal, and stemming.
- **Model Training**: Different classification models (KNN, Random Forest, Naive Bayes, SVM).
- **Sentiment Labeling**: Reviews are categorized as **Positive**, **Neutral**, or **Negative** based on the score of the review.
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1 Score, and Confusion Matrix to evaluate model performance.

## Setup ⚙️

To get started with this project, you can follow the steps below:

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/sentiment-analysis-bank-reviews.git
cd sentiment-analysis-bank-reviews
```

### 2. Install Dependencies 🧰

You can install the required libraries using the following command:

```bash
pip install -r requirements.txt
```

### 3. Run the Code 🚀

Once the dependencies are installed, you can run the analysis script to train the models and evaluate their performance.

```bash
python sentiment_analysis.py
```

### 4. Visualize Results 📊

The project also provides visualizations for the sentiment distribution and confusion matrices for each classifier. These visualizations can be viewed after running the main script.

## Classifiers Used 🧑‍💻

- **K-Nearest Neighbors (KNN)**
- **Random Forest Classifier**
- **Naive Bayes Classifier**
- **Support Vector Machine (SVM)**

## Evaluation Metrics 🏅

- **Accuracy**: Measures the overall accuracy of the model.
- **Precision**: Measures the percentage of true positive predictions.
- **Recall**: Measures the percentage of actual positive instances correctly predicted.
- **F1 Score**: The harmonic mean of precision and recall.
- **Confusion Matrix**: A matrix used to visualize the classification results.

## Visualizations 📈

- Sentiment distribution for different Indonesian banks over the years.
- Top 10 most frequent words in positive, neutral, and negative reviews for each bank.

## Project Structure 🗂️

```
.
├── data
│   └── dataPerbankan.csv       # The dataset used for sentiment analysis
├── scripts
│   └── sentiment_analysis.py   # Main script for analysis and model training
│   └── preprocessing.py        # Preprocessing steps (normalization, tokenization, etc.)
├── requirements.txt            # List of dependencies
└── README.md                   # Project documentation
```

