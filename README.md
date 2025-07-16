## Personality-Classification
Personality Classification Based on Social Media and Big Five Personality Categories Using Logistic Regression

This repository contains the code and dataset structure used in a research project that focuses on classifying user personality based on their tweets using the Big Five Personality model and the Logistic Regression algorithm.

## 📌 Overview
This project aims to classify personalities into five categories (Openness, Conscientiousness, Extraversion, Agreeableness, and Neuroticism) based on public tweets from the social media platform X (formerly Twitter).

The classification process involves multiple experiments using various scenarios:
- Different preprocessing strategies
- Multiple data split ratios (70:30 and 80:20)
- Feature extraction methods such as TF-IDF, Bag-of-Words, and N-Grams
- Data balancing techniques including SMOTE and random deletion augmentation

## 🗂️ Dataset
- Total tweets: 233,393
- Total users: 257
- Personality labels were collected via a personality survey using the BFI-44 (Big Five Inventory-44) questionnaire.
- All tweets from each user were combined into a single row to ensure classification is done per user.
⚠️ Note: The dataset used in this research contains personal information and is not publicly available due to privacy and ethical considerations.

## 🧪 Methodology
1. Data Preprocessing (Cleaning, Tokenizing, Normalizing, Stemming, etc.)
2. Splitting Data into train and test sets (70:30 and 80:20)
3. Balancing Techniques:
   - SMOTE for oversampling minority classes
   - Random Deletion Augmentation for undersampling majority classes
4. Feature Extraction using:
   - TF-IDF
   - Bag-of-Words
   - N-Grams
   - Combinations of the above
5. Model Training using Multinomial Logistic Regression
6. Evaluation using Accuracy, Precision, Recall, and F1-score

## 📊 Result Highlights
The highest accuracy (71%) was achieved using:
  - Preprocessing scenario 2
  - 70:30 data split
  - Random Deletion balancing
  - TF-IDF + Bag-of-Words feature combination
