# Spam-Mail-Classifier

##  Overview
This project builds a machine learning model to classify messages as **Spam** or **Ham (Not Spam)** using natural language processing techniques.

It uses the **SMS Spam Collection dataset** and implements two models:
- Naive Bayes
- Logistic Regression

---

##  Features
- Text preprocessing (lowercasing, tokenization, stopword removal)
- Feature extraction using **TF-IDF**
- Model training and evaluation
- Accuracy, precision, recall, and F1-score metrics
- Custom input prediction with probability outputs

---

##  Dataset
The dataset is automatically downloaded from the UCI repository.

It contains labeled SMS messages categorized as:
- `spam`
- `ham`

---

##  Installation

Run the following command:

    pip install pandas scikit-learn nltk

---

##  How to Run

1. Clone the repository:

    git clone https://github.com/your-username/spam-mail-detector.git
    cd spam-mail-detector

2. Run the script:

    python spam_detector.py

---

##  Workflow

1. Download and load dataset  
2. Preprocess text data  
3. Convert text into numerical features (TF-IDF)  
4. Split data into training and testing sets  
5. Train models (Naive Bayes & Logistic Regression)  
6. Evaluate performance  
7. Predict new messages  

---

##  Models Used

### 🔹 Naive Bayes
- Fast and efficient for text classification  
- Works well with word frequencies  

### 🔹 Logistic Regression
- More flexible decision boundary  
- Provides probability outputs  

---

##  Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

---

##  Example

Input:
    Congratulations! You won a free iPhone. Click now!

Output:
    Prediction: SPAM
    Probability: [0.02, 0.98]

---

##  Future Improvements
- Use deep learning (LSTM / Transformers)
- Deploy as a web application
- Improve preprocessing with stemming or lemmatization

---

## 👨‍💻 Author
Ojas Sahu
