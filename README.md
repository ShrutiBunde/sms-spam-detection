## SMS Spam Detection Using Python + Machine Learning

### Project Overview :
This project builds a Machine Learning model that classifies SMS messages as:

* Spam → Unwanted / promotional / fraudulent messages

* Ham → Legitimate messages

The system uses Natural Language Processing (NLP) techniques and ML algorithms to automatically detect spam messages.


### Problem Statement : 
Classify SMS messages into Spam or Ham (Not Spam) using Machine Learning.

Spam messages are a major issue in communication systems, and this project demonstrates how ML can help filter unwanted content.


### Dataset :
    The dataset contains labeled SMS messages:
        -  Text Message
        -  Label (Spam / Ham)

Typical examples:
Message	                                   Label
"Congratulations! You won a free prize"	   Spam
"Hey, are we meeting today?"	           Ham


### Project Workflow :
The project follows a standard ML pipeline:
1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Text Preprocessing
5. Feature Engineering
6. Model Training
7. Model Evaluation
8. Parameter Tuning
9. Model Comparison
10. Prediction Demo


### Text Preprocessing : 
The SMS text was processed using NLP techniques:
- Lowercasing
- Removing punctuation
- Removing stopwords
- Stemming

Example:
Original:
"Congratulations! You won a FREE lottery prize!!!"

Processed:
"congratul free lotteri prize"


### Feature Engineering : 
Text data was converted into numerical form using:
- TF-IDF Vectorization
This helps the model understand word importance.


### Models Used :
Multiple ML algorithms were trained:
- Multinomial Naive Bayes
- Random Forest Classifier
- Logistic Regression


### Model Evaluation Metrics : 
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix


### Prediction Demo :
The saved model was tested on new SMS messages.
Input:
"URGENT! Claim your FREE cash reward now!!!"

Prediction:
Spam
This confirms real-world usability.


### Model Saving :
The trained model and vectorizer were saved using:
- spam_model.pkl
- vectorizer.pkl
Allows reuse without retraining.


### Future Improvements :
- Deep Learning models (LSTM / Transformers)
- Deploy as Web App (Streamlit / Flask)
- Real-time SMS filtering system
- Larger dataset training


### Key Learnings :
- NLP preprocessing techniques
- TF-IDF feature extraction
- Model evaluation & comparison
- Practical ML pipeline design


### Author :
Shruti Bunde
Machine Learning / Data Science Enthusiast 🚀

