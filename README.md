# FUTURE_ML_02 – Support Ticket Classification

## 📌 Project Overview

This project was developed as part of the Future Interns Machine Learning Internship.

The objective is to build a Machine Learning system that automatically classifies customer support tickets into appropriate support categories and assigns priority levels.

## 🎯 Objectives

- Classify customer support tickets into different support queues.
- Predict ticket priority as High, Medium, or Low.
- Apply NLP techniques for text preprocessing.
- Convert text into numerical features using TF-IDF.
- Evaluate model performance.
- Analyze classification errors.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- NLTK
- Google Colab
- Jupyter Notebook

## 🔄 Project Workflow

1. Dataset loading
2. Data exploration
3. Text preprocessing
4. Subject and body combination
5. Text cleaning
6. Tokenization
7. TF-IDF feature extraction
8. Train-test split
9. Support queue classification
10. Priority classification
11. Model evaluation
12. Confusion matrix analysis
13. Error analysis
14. Final ticket prediction

## 📊 Model Results

### Support Queue Classification

**Accuracy: 47.55%**

The model classifies tickets into 10 support categories.

### Priority Classification

**Accuracy: 54.74%**

The model predicts three priority levels:

- High
- Medium
- Low

## 🔎 Error Analysis

The major classification errors occurred between similar support categories.

The most frequent confusion was:

**Product Support → Technical Support: 444 tickets**

Other common errors included:

- IT Support → Technical Support
- Customer Service → Technical Support
- Technical Support → Product Support

This indicates that tickets containing similar technical and support-related language can be difficult for a TF-IDF-based classifier to distinguish.

## 🎫 Sample Prediction

Example ticket:

**Subject:** Unable to access my account

**Prediction:**
- Queue: Technical Support
- Priority: HIGH

## 💼 Business Value

This system can help customer support teams:

- Automatically route incoming tickets.
- Identify high-priority requests.
- Reduce manual ticket classification.
- Improve response organization.
- Support faster handling of customer issues.

## 📌 Conclusion

The project demonstrates the use of Natural Language Processing and Machine Learning for automated support ticket classification and priority prediction.

The error analysis also provides useful insights into areas where the model can be improved using more advanced NLP techniques and better handling of similar ticket categories.

## 👩‍💻 Internship

**Future Interns – Machine Learning Internship**

**Task 2: Support Ticket Classification**
