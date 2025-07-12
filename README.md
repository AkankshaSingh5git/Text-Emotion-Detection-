# Text-Emotion-Detection




## Overview

This project focuses on automatically detecting emotions from text using natural language processing (NLP) and machine learning.  
Given a piece of text (like a tweet, message, or sentence), the model can predict which emotion it expresses, such as joy, sadness, anger, fear, love, or surprise.

The system can be useful for social media monitoring, mental health applications, customer feedback analysis, and more.

## Dataset

The dataset used in this project is uploaded directly to this repository (`emotion_dataset_raw.csv`).  
It includes text samples labeled with their corresponding emotions.

## Files

- `app.py` — Script for deploying the trained model as a web app (e.g., using Streamlit).
- `Text_emotion_detection.ipynb` — Main notebook for data preprocessing, training, and evaluating the model.
- `text-emotion-detection.ipynb` — Additional experiments and visualizations.
- `emotion_dataset_raw.csv` — Raw dataset containing text and emotion labels.
- `text_emotion.pkl` — Serialized (saved) model or tokenizer for prediction.

## Approach

1. **Data Preprocessing**: Text is cleaned, tokenized, and converted into numerical vectors using techniques like TF-IDF or embeddings.
2. **Model Training**: Various classifiers (e.g., Logistic Regression, SVM, or deep learning models) are trained to learn emotion patterns.
3. **Evaluation**: The model is evaluated using metrics like accuracy, precision, recall, and F1-score.
4. **Deployment**: The trained model is wrapped into a web app for easy interactive predictions.

## How to Run

1. Clone this repository:

```bash
git clone https://github.com/AkankshaSingh5git/Text-Emotion-Detection.git
```







## Results

The model demonstrates strong performance in accurately classifying emotions from text data.  
It can generalize well to new inputs and shows robust results across multiple emotion categories such as joy, sadness, anger, fear, love, and surprise.  
With further tuning and larger datasets, it can be integrated into real-world applications for real-time emotion analysis and monitoring.



## Research Paper

This project work has also been published as a research paper to further demonstrate its novelty and contribution to the field of emotion analysis.

[A Novel Approach to determine wellness quotient of a society] — [ICCCIS], [205].  



  







