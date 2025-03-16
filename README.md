# Stock Sentiment Analysis

This project uses Natural Language Processing (NLP) and Machine Learning to predict stock market movements based on news headlines. The model classifies whether the stock price will go up or stay the same/go down based on sentiment analysis.

## 📌 Features
- **Data Preprocessing:** Cleans and processes financial news headlines.
- **Text Vectorization:** Uses Bag of Words (BoW) with n-grams.
- **Machine Learning Models:**
  - Logistic Regression
  - Random Forest Classifier
  - Multinomial Naive Bayes
- **Visualization:** Word clouds and confusion matrices for better insights.
- **Stock Prediction Function:** Predicts sentiment based on new headlines.

## 📂 Dataset
The dataset contains historical news headlines with labels:
- `1`: Stock price goes up.
- `0`: Stock price remains the same or goes down.

## 🛠️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/stock-sentiment-analysis.git
   cd stock-sentiment-analysis
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download NLTK stopwords:
   ```python
   import nltk
   nltk.download('stopwords')
   ```


## 📊 Model Performance
| Model                 | Accuracy |
|----------------------|---------|
| Logistic Regression | 85%     |
| Random Forest       | 84%     |
| Naive Bayes         | 83%     |

## 📌 Improvements & Future Work
- Implement advanced NLP models like **Word2Vec** or **BERT**.
- Improve feature selection with **TF-IDF**.
- Explore **deep learning models (LSTMs, Transformers)**.

## 🤝 Contributing
Feel free to fork the repository, make changes, and submit a pull request!
