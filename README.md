# Sentiment Analysis of Social Media Posts using Machine Learning

This project performs **sentiment analysis** on social media posts using
**Python** and **Machine Learning**.\
It demonstrates a simple ML workflow using `TfidfVectorizer` and
`LogisticRegression` to classify text as **Positive** or **Negative**.

------------------------------------------------------------------------

## 🔍 Features

-   Converts text data into numerical vectors using **TF-IDF**
-   Splits dataset into **training** and **testing** sets
-   Trains a **Logistic Regression classifier**
-   Predicts sentiment of new social media posts
-   Shows **model accuracy**

------------------------------------------------------------------------

## 📂 Code Overview

### **1. Import Libraries**

The following libraries are used: - `train_test_split` for splitting
data\
- `TfidfVectorizer` for feature extraction\
- `LogisticRegression` for classification\
- `accuracy_score` for evaluation

### **2. Sample Dataset**

A small example dataset of positive/negative posts is included.\
You can replace this list with your own dataset.

### **3. TF-IDF Vectorization**

Converts text to numerical vectors used for model training.

### **4. Model Training**

The model is trained using:

    LogisticRegression()

### **5. Prediction**

Predicts whether a new post is **Positive** or **Negative**.

------------------------------------------------------------------------

## 📌 Example Output

    Accuracy: 0.5
    Sentiment: Negative

------------------------------------------------------------------------

## ▶️ How to Run

1.  Install required libraries:

```{=html}
<!-- -->
```
    pip install scikit-learn

2.  Save the Python script and run it:

```{=html}
<!-- -->
```
    python sentiment_analysis.py

------------------------------------------------------------------------

## 📦 Dependencies

-   Python 3.x\
-   scikit-learn

------------------------------------------------------------------------

## 📜 License

This project is open-source and free to use.

------------------------------------------------------------------------

## 🤝 Contributing

Pull requests are welcome. Feel free to open issues for improvements.
# AI-AND-ML-PROJECT
