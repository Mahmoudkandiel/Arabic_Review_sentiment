---
# Arabic Review Sentiment Analysis

This project implements sentiment analysis for Arabic text reviews using the **AraBERTv02** model. The model is fine-tuned on a dataset of 100,000 Arabic reviews to classify sentiment as **positive**, **negative**, or **neutral**.

## Project Overview

The objective of this project is to perform sentiment analysis on Arabic text reviews by leveraging the AraBERTv02 model, a pre-trained BERT variant specifically for Arabic language tasks. The sentiment classification model is trained on a dataset of 100,000 labeled Arabic reviews.

## Technologies Used

- **AraBERTv02**: A pre-trained BERT model for Arabic language processing, fine-tuned on the sentiment analysis task.
- **Dataset**: A collection of 100,000 Arabic reviews with sentiment labels (positive, negative, neutral).
- **Libraries**:
  - `transformers` (Hugging Face) for model loading and fine-tuning.
  - `torch` for deep learning operations.
  - `pandas` for data handling and preprocessing.
  - `scikit-learn` for model evaluation metrics.

## Dataset

The dataset contains 100,000 labeled Arabic reviews with the following sentiment categories:

- **Positive**
- **Negative**
- **Neutral**

Each record includes the review text and its associated sentiment label.

## Model

- **AraBERTv02**: This model is a transformer-based architecture pre-trained on large-scale Arabic text. It has been fine-tuned for sentiment analysis to classify reviews into three sentiment categories.

## How to Use

- The model can be used to predict the sentiment of Arabic reviews by providing the review text to the trained model.
- The model output will be one of the following categories: **Positive**, **Negative**, or **Neutral**.

---
