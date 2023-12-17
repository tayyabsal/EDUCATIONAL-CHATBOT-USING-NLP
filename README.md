# EDUCATIONAL-CHATBOT-USING-NLP


# Chatbot Intent Classification with BERT

This project involves building a chatbot intent classification model using BERT (Bidirectional Encoder Representations from Transformers). The goal is to predict the intent or category of a given user query.

## Dataset

The dataset is loaded from a JSON file containing patterns and corresponding tags. Each pattern represents a user query, and the tag indicates the intent or category.

## Getting Started

1. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn wordcloud missingno nltk torch transformers tensorflow keras
   ```

2. Run the provided Python script:

   ```bash
   python chatbot_classification.py
   ```

## Data Exploration

- The dataset is loaded and explored using Pandas.
- Information about the dataset, such as shape and data types, is displayed.

## Text Analysis

- WordCloud and n-gram analysis are performed to explore the most common words and phrases in the dataset.

## Model Training

- BERT (bert-base-uncased) is used for sequence classification.
- The dataset is split into training and testing sets.
- A DataLoader class is defined to facilitate loading data into PyTorch.

## Training Arguments

- Training arguments, including output directory, batch size, and evaluation strategy, are configured using the `TrainingArguments` class from the `transformers` library.

## Model Training

- The model is trained using the defined training arguments.
- Training progress is logged and saved to the specified output directory.

## Model Prediction

- The trained model can be used to predict the intent of user queries.
- The `predict` function takes a text input, tokenizes it using the BERT tokenizer, and provides the predicted intent label.

## Save Model

- The trained model and tokenizer are saved for future use.

## Project Structure

- `chatbot_classification.py`: The main Python script containing code for data loading, preprocessing, model training, and prediction.
- `innnnnnn.json`: JSON file containing chatbot intents and patterns.

Feel free to customize the code and explore further!

```



