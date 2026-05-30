
BBC News Classification using NLP and Naive Bayes

Project Overview

This project classifies news articles into different categories using Natural Language Processing (NLP) techniques and the Multinomial Naive Bayes algorithm.

The model takes a news article as input and predicts its category among the following classes:

- Business
- Sport
- Politics
- Entertainment
- Tech

---

Dataset

Dataset: BBC News Classification Dataset

Features:

- Article: News article text
- Category: Target class

Total Categories: 5

---

Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- TF-IDF Vectorizer
- Multinomial Naive Bayes

---

Machine Learning Workflow

1. Load Dataset
2. Data Exploration
3. Check Missing Values
4. Analyze Category Distribution
5. Text Vectorization using TF-IDF
6. Train-Test Split
7. Train Multinomial Naive Bayes Model
8. Evaluate Model Performance
9. Generate Confusion Matrix
10. Generate Classification Report
11. Predict News Category from Custom Input

---

Model Performance

Accuracy: 95.64%

Precision: 95.75%

Recall: 95.64%

F1 Score: 95.63%

---

Confusion Matrix

A confusion matrix heatmap was used to visualize classification performance across all news categories.

---

Example Prediction

Input:

India won the T20 World Cup by defeating South Africa.

Output:

Predicted Category: Sport

Top Predictions:

- Sport: 48.57%
- Business: 20.93%
- Entertainment: 17.29%

---

Key Learnings

- Natural Language Processing (NLP)
- Text Vectorization using TF-IDF
- Multiclass Classification
- Multinomial Naive Bayes
- Model Evaluation using Accuracy, Precision, Recall and F1 Score
- Confusion Matrix Visualization

---

Future Improvements

- Deploy using Streamlit
- Add Text Preprocessing Pipeline
- Compare with Logistic Regression and Random Forest
- Build a Web-Based News Classification Application

---

Author

Soumotirtha Das

B.Tech Information Technology

RCC Institute of Information Technology
