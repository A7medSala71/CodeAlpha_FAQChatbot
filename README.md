# CodeAlpha_FAQChatbot

This project is a console-based FAQ Chatbot developed as part of the CodeAlpha Internship Program. It uses Natural Language Processing (NLP) techniques to match user input with predefined FAQs and return the most appropriate response.

## Project Overview

The chatbot uses spaCy for preprocessing (tokenization, lemmatization, stopword removal), and scikit-learn for converting text into TF-IDF vectors. Cosine similarity is then used to identify the closest match between user questions and stored FAQ entries.

## Features

- Predefined FAQ question-answer pairs
- Text preprocessing using spaCy
- TF-IDF vectorization and cosine similarity matching
- Simple console-based interface (compatible with Google Colab and standard Python interpreters)

## File Structure

CodeAlpha_FAQChatbot/
│
├── faq_chatbot.py        # Main Python script for the chatbot
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation

## Requirements

- Python 3.x
- spaCy
- scikit-learn

To install the required libraries:

pip install -r requirements.txt
python -m spacy download en_core_web_sm

## How to Run

To run the chatbot in your terminal or in a Google Colab notebook:

python faq_chatbot.py

You will be prompted to type a question. Type 'exit' to quit the chatbot.

## Sample Questions

You can ask questions such as:

- What is your return policy?
- How do I track my order?
- Do you offer international shipping?
- What payment methods do you accept?

## Author

Ahmed Salah  
Developed for the CodeAlpha Internship Program, 2025.
