# sms_spam_detector
## Overview

This project focuses on creating an SMS text classification model capable of detecting spam messages. A Gradio interface is provided to allow users to input SMS messages and receive real-time predictions on whether the message is spam or ham.

The classification model is built using natural language processing (NLP) techniques, and the Gradio library facilitates the interaction between the model and the user.

## Features

- Classifies SMS messages as spam or ham.
- Interactive Gradio web interface for testing the model.
- Machine learning techniques for text preprocessing and classification.
- Real-time prediction feedback through the Gradio UI.

## Installation

1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2. Navigate to the project directory:
    ```bash
    cd sms-text-classification
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the Gradio interface locally, execute the following command:

```bash
jupyter notebook gradio_sms_text_classification.ipynb
```

This will open the Jupyter Notebook containing the code for training and evaluating the SMS classification model, as well as launching the Gradio UI.

## Model Overview

The model uses the following key steps for classification:
- **Text Preprocessing**: Tokenization, stopword removal, and vectorization.
- **Model Training**: Utilizes machine learning models such as Naive Bayes, Logistic Regression, or Support Vector Machines (SVM) to classify SMS messages.
- **Prediction**: After training, the model can classify unseen text as either spam or ham.

## Dataset

The dataset used for training the model contains SMS messages labeled as either "ham" (non-spam) or "spam." The data is preprocessed before being fed into the model for training.

## Results

The performance of the model can be evaluated based on metrics such as accuracy, precision, recall, and F1-score. The final results will depend on the training dataset and the model selected for classification.

## Gradio Interface

The Gradio interface allows users to input text messages and get real-time predictions on whether the message is spam or ham. The interface is simple and user-friendly, designed to make testing easy.

To interact with the interface, simply type or paste your SMS message into the input box and click the "Submit" button. The model will then output a prediction label.

