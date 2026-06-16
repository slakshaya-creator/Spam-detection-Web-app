#  Spam Detection System

A simple machine learning-based web application that classifies messages as *Spam* or *Not Spam* using Python and NLP techniques.

##  Overview

This project converts raw text messages into numerical features and applies a classification algorithm to detect spam. Built and demonstrated in Jupyter Notebook.

##  Tech Stack

- *Language:* Python
- *Libraries:* scikit-learn, pandas, numpy
- *NLP:* CountVectorizer / TF-IDF (text to numerical conversion)
- *Algorithm:* Naive Bayes / Logistic Regression
- *Environment:* Jupyter Notebook

##  Project Structure# ⚙️ How It Works

1. Raw text messages are loaded and labeled (spam / not spam)
2. Text is converted into numerical vectors using CountVectorizer or TF-IDF
3. A classification model is trained on the vectorized data
4. The model predicts whether a new input message is spam or not

##  Getting Started

bash
# Clone the repo
git clone https://github.com/slakshaya-creator/Spam-detection-Web-app.git
cd Spam-detection-Web-app

# Install dependencies
pip install scikit-learn pandas numpy jupyter

# Run the notebook
jupyter notebook "spam detection.ipynb"


##  Output

- Input: A text message
- Output: Spam or Not Spam

##  Author

*S. Lakshaya* 
