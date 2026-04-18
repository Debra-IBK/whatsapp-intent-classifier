# WhatsApp Business Message Intent Classifier

A machine learning model that automatically identifies the intent behind WhatsApp business messages classifying them into actionable categories to enable smarter AI-powered business advisory tools.

## Overview

Business owners communicate their needs in natural, conversational language. This classifier analyses incoming WhatsApp messages and instantly identifies what type of help they need — enabling faster, more accurate AI responses.

## Intent Categories

| Intent | Example Message |
|--------|----------------|
| Pricing | "How much should I charge for my service?" |
| Marketing | "How do I get more customers?" |
| Financial | "Should I take out a business loan?" |
| Customer Issues | "My client hasn't paid me in 3 weeks" |
| Growth | "Should I hire my first employee?" |

## How It Works

1. Raw WhatsApp messages are collected and labelled by intent
2. Text is converted to numerical vectors using TF-IDF
3. A Naive Bayes classifier learns patterns from labelled examples
4. New messages are classified in real time
5. Results guide AI response generation

## Results

- **Accuracy:** 70% on test data with 50 training examples
- **Perfect classification:** Customer Issues and Growth categories
- **Real world test:** 5/5 correct on unseen messages

## Tech Stack
- Python
- Scikit-learn
- Pandas
- NumPy
- Jupyter Notebook

## Real World Application

This classifier forms the foundational intent recognition layer for **Sabi** — a WhatsApp-based AI business advisor built for African entrepreneurs. By understanding what a business owner needs before responding, Sabi delivers more accurate, contextually relevant advice.

## Future Improvements

- Expand training dataset to 500+ messages
- Add new intent categories including Motivation and Supplier Management
- Train on real entrepreneur messages for better accuracy
- Integrate Pidgin English and informal language patterns
- Connect to live WhatsApp Business API
