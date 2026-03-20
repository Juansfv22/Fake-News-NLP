# Fake-News-NLP

# Fake News Detection with NLP 📰🚫

This project applies **Natural Language Processing (NLP)** techniques and supervised learning to classify news as true or false.

[![Open In Colab](https://colab.research.google.com)](https://colab.research.google.com/drive/1lAS4PmovfqvCOFxXQhEJkEfbFiL_qUqE)

## The Corpus
A balanced dataset of **5,200 news articles** in Spanish was constructed:
*   **2,600 True:** Extracted from reliable newspapers and specialized datasets.
*   **2,600 False:** Sourced from low-credibility sites and web scraping techniques.
*   *Note: 4% of the corpus (200 articles) was obtained through custom web scraping.*

## Methodology and Experiments
The project evaluates the impact of normalization and vectorization on model performance:

1.  **Preprocessing:** Cleaning, stopword removal, and **stemming**.
2.  **Vectorization:** Comparison between **TF-IDF** and **Term Occurrence (TO)**.
3.  **Evaluated Models:** 
    *   Logistic Regression (LR)
    *   Decision Tree (DT)
    *   K-Nearest Neighbors (KNN)
    *   Support Vector Classifier (SVC)
4.  **Success Metric:** The **F1-Score** is used to compare algorithms under different configurations (with/without normalization and different vectorization methods).

## How to use this Notebook
The notebook is structured into two main blocks:
1.  **Section 1 (Extraction):** Evidence of web scraping and initial cleaning (requires manual upload of external datasets).
2.  **Section 2 onwards (Processing and Training):** Direct access to the processed corpus via automatic download from Google Drive, application of techniques, model training, and metric calculation.

## Process and results
The experiments yielded highly **positive** results, demonstrating high f1-score in news classification. The application of normalization techniques and TF-IDF allowed the models to achieve outstanding performance.

For a detailed analysis of preprocessing, techniques, metrics and algorithm comparisons, please refer to the **attached PDF file** in this repository.


## Collaborations
I'm not accepting pull requests or contributions. However, feel free to fork and use this code for your own purposes.
