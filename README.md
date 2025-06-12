# 🗞️ News Group Classification (NLP Project)

This project is a text classification pipeline that classifies news articles into multiple categories using machine learning techniques and natural language processing (NLP).

## 📁 Dataset
- The dataset was provided as part of a university assignment.
- It contains news articles grouped into predefined categories.
- Preprocessing was performed manually to extract text and labels.

## ⚙️ Features & Tools
- **Language**: Python
- **Libraries**: Scikit-learn, Pandas, Matplotlib, NLTK
- **Models Used**: Multinomial Naive Bayes, Logistic Regression
- **Vectorization**: TF-IDF
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score, Confusion Matrix

## 🧠 Project Pipeline
1. **Data Loading**  
   News articles and labels loaded from pre-cleaned files.
2. **Text Preprocessing**  
   Tokenization, lemmatization, and stopword removal.
3. **Feature Extraction**  
   TF-IDF vectorization to convert text into numerical features.
4. **Model Training & Evaluation**  
   Trained and tested multiple classifiers, evaluated using classification report and confusion matrix.
5. **Performance**  
   Achieved ~81–82% accuracy with Multinomial Naive Bayes.

## 📊 Results
- Logistic Regression and Naive Bayes performed best.
- Visualizations include classification report and confusion matrix.
