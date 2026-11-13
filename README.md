# ITNPA4-34-Project
Natural Language Processing with Python Project documentations
## 1. Project Overview

The Research Papers Expert System is a machine-learning application developed to classify research paper abstracts into two categories: Artificial Intelligence (AI) and Classical research.

The system uses Natural Language Processing (NLP) techniques to prepare text for classification. TF-IDF is used to convert the text into numerical features that can be processed by machine-learning algorithms.

## 2. Objectives

The main objectives of the project are to:

- Preprocess research paper abstracts for classification.
- Train and evaluate different machine-learning models.
- Compare model performance using classification evaluation metrics.
- Develop a simple web application that allows users to enter a research abstract and receive a predicted category.

## 3. Machine-Learning Models

The project compares the following classification algorithms:

- Multinomial Naive Bayes
- Linear Support Vector Classification (LinearSVC)
- Random Forest
- Gradient Boosting
- Logistic Regression with hyperparameter tuning

The tuned Logistic Regression model is used in the application if it is the final model selected during evaluation.

## 4. Technologies Used

- Python
- Pandas
- Scikit-learn
- Natural Language Processing (NLP)
- TF-IDF Vectorisation
- Streamlit
- Joblib

## 5. Project Files

The deployment folder contains the following files:

- `app.py` – the Streamlit application.
- `best_model.pkl` – the saved trained machine-learning pipeline.
- `requirements.txt` – the Python libraries required to run the application.
- `README.md` – project description and setup instructions.

## 6. Installation and Setup

1. Install Python and ensure that pip is available.
2. Open Anaconda Prompt or a terminal.
3. Navigate to the deployment folder.
4. Install the required packages by running:

   `pip install -r requirements.txt`

## 7. Running the Application

Run the following command from the deployment folder:

`python -m streamlit run app.py`

Streamlit will display a local URL in the terminal. Open that URL in a web browser to access the application.

## 8. Using the Application

1. Open the Research Papers Expert System in your browser.
2. Enter or paste a research paper abstract into the text field.
3. Submit the text for classification.
4. View the predicted category returned by the model.

## 9. Limitations

The predictions depend on the training dataset and the performance of the selected model. The system provides an automated classification and should not be treated as a replacement for expert academic judgement.

## 10. Conclusion

The project demonstrates how machine-learning and NLP techniques can be applied to research paper classification. The web application provides a simple interface for testing the trained model on new research abstracts.
