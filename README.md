# Sentiment Analysis Using Deep Learning

This project uses **BERT (Bidirectional Encoder Representations from Transformers)** for sentiment and emotion analysis on online platforms like Twitter. It classifies text as **positive, negative, or neutral**, tracks emotional trends, and identifies potential signs of harassment or distress.


## ✨ Features
- Fine-tuned BERT model for accurate sentiment classification  
- Real-time sentiment and emotion detection  
- Handles code-mixed/multilingual content  
- Visualizations: sentiment distribution, confusion matrix, word clouds, and trend graphs  
- Modular design for easy scalability and integration  


## 📂 Project Structure
```
├── data/ # Dataset samples (Sentiment140/SMILE links in README)
├── src/ # Source code (preprocessing, training, evaluation)
├── notebooks/ # Jupyter notebooks
├── tests/ # Unit & integration tests
├── docs/ # Report and documentation
├── requirements.txt # Dependencies
├── .gitignore # Ignored files
└── README.md # Project overview
```

## ⚙️ Installation
```bash
git clone https://github.com/ShrayHub/Sentiment-Analysis-Using-Deep-Learning
cd Sentiment-Analysis-Using-Deep-Learning
pip install -r requirements.txt

## 📊 Outputs & Results

### Sentiment Distribution
![Emotion Distribution](docs/images/emotion_distribution.png)

### Input Length Analysis
![Input Length](docs/images/input_length.png)

### Training Tweets (Length < 10 Words)
![Training Tweets](docs/images/train_tweets.png)

### Test Tweets (Length < 10 Words)
![Test Tweets](docs/images/test_tweets.png)

### BERT Classification Report
![Classification Report](docs/images/classification_report.png)

### Confusion Matrix
![Confusion Matrix](docs/images/confusion_matrix.png)

---

### ✅ Results
- Achieved a **Weighted F1 Score of 86%** on the SMILE dataset  
- Outperformed traditional ML methods (Naive Bayes, SVM, Logistic Regression)  
- Accurately handled short-form tweets and informal language  
- Identified sentiment trends and potential harassment patterns effectively
