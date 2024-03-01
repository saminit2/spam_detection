# Spam Detection using Multinomial Naive Bayes Classifier
File Structure

*'spam_detection.py'*: Main Python script containing the code for loading data, training the model, evaluating the model, and testing with sample messages.

*'emails.csv'*: Sample dataset containing email messages labeled as spam or not spam.

*'CLF_MultinomialNB_CountVectorizer_spam_detection_test_size_0.2.pkl'*: Trained model saved as a pickle file.

*'README.md'*: This file containing information about the project.



This repository contains code for a simple spam detection system using the Multinomial Naive Bayes classifier. The classifier is trained on a dataset of emails labeled as spam or not spam.

## Features

- **Data Loading and Preprocessing**: The code loads email data from a CSV file and preprocesses it for training.
- **Model Training**: It trains a Multinomial Naive Bayes classifier using scikit-learn.
- **Model Evaluation**: The trained model is evaluated using a test set, and the accuracy and confusion matrix are displayed.
- **Model Persistence**: The trained model is saved using pickle for future use.
- **Sample Prediction**: The user can input sample messages to test the trained model.

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib

## Usage

1. Clone the repository:

***git clone https://github.com/saminit2/spam-detection.git***

***cd spam-detection***


2. Install the required dependencies:

***pip install -r requirements.txt***

3. Run the main script:

***python spam_detection.py***

**Follow the prompts to test the trained model with sample messages.**


# *Contributing*
Contributions are welcome! Please feel free to submit issues or pull requests.

# *License*
This project is licensed under the MIT License - see the LICENSE file for details.


***Feel free to modify and customize this template according to your specific project details and preferences.***

