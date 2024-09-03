# Drug Review Analysis

## Overview

This project involves the analysis of patient reviews on specific drugs related to various conditions, accompanied by a 10-star patient rating reflecting overall satisfaction. The dataset was obtained by crawling online pharmaceutical review sites and is designed to explore multiple facets of sentiment analysis, including:

1. **Sentiment analysis of drug experiences** over various aspects such as effectiveness, side effects, and overall satisfaction.
2. **Transferability of models across different conditions**, examining how well models trained on one condition can generalize to others.
3. **Transferability of models across different data sources**, evaluating the robustness and generalization of sentiment analysis models on different datasets.

The dataset is divided into two parts: a training set (75%) and a test set (25%), stored in tab-separated values (.tsv) files.

## Project Structure

The project is organized into the following parts:

1. **Drug Review Analysis - Part 1**:
   - Introduction to the dataset and basic exploratory data analysis (EDA).
   - Overview of the initial preprocessing steps and data cleaning.

2. **Drug Review Analysis - Sentiment Analysis**:
   - Detailed sentiment analysis of drug reviews.
   - Model development and evaluation for sentiment classification.
   - Performance metrics and comparison of different models.

3. **Drug Review Analysis - Text Modelling**:
   - Advanced NLP techniques for text modeling.
   - Implementation of machine learning models to predict sentiments based on review text.
   - Transfer learning approaches to evaluate model performance across different conditions.

4. **Drug Review Analysis - Text Generation**:
   - Exploration of text generation models for generating drug reviews.
   - Use of techniques like LSTM and GPT for text synthesis.
   - Evaluation of the quality and relevance of generated text.

## Dataset Information

- **Source**: UCI Machine Learning Repository (via Druglib.com)
- **Data Format**: Tab-separated values (.tsv) files
- **Partitions**: 
  - Train Set: 75%
  - Test Set: 25%
- **Attributes**:
  - Drug Name
  - Condition
  - Review
  - Rating (1-10 scale)
  - Date
  - Useful Count

## Project Goals

The primary goals of this project are to:

1. Perform **sentiment analysis** on drug reviews to identify and classify sentiments related to specific drug effects and patient experiences.
2. Study the **transferability** of sentiment analysis models across different conditions and data sources.
3. Develop and fine-tune machine learning models to predict sentiments and ratings based on review text.
4. Explore **text generation** techniques to create synthetic drug reviews.

## Methodology

1. **Data Preprocessing**:
   - Clean and preprocess the text data (e.g., removing stop words, stemming, and tokenization).
   - Handle missing values and normalize the ratings.
  
2. **Exploratory Data Analysis (EDA)**:
   - Visualize the distribution of ratings, conditions, and drugs.
   - Perform sentiment analysis to explore the relationship between review text and ratings.

3. **Modeling**:
   - Train and evaluate various machine learning models (e.g., Logistic Regression, SVM, Random Forest) for sentiment analysis.
   - Experiment with deep learning models like LSTM, BERT for advanced sentiment classification.

4. **Transfer Learning**:
   - Investigate model performance across different conditions and datasets.
   - Evaluate how well models trained on one subset of data perform on another.

5. **Text Generation**:
   - Implement and evaluate models for generating drug reviews.
   - Explore the use of LSTM, GPT, and other techniques for text synthesis.

6. **Evaluation**:
   - Use metrics such as accuracy, F1-score, precision, recall, and AUC to evaluate model performance.
   - Compare model performance on training and test datasets.

## Results

- Detailed results of the sentiment analysis, model performance, and insights into model transferability will be provided.
- Generated text reviews will be evaluated for relevance and coherence.

## Future Work

- Extend the analysis to more granular aspects of drug reviews (e.g., specific side effects).
- Incorporate additional datasets for broader model validation.
- Explore other NLP techniques for improving sentiment classification accuracy and text generation.

## Usage

To use this dataset:

1. **Clone the repository**: `git clone <repository_url>`
2. **Install dependencies**: 
   ```bash
   pip install -r requirements.txt
   ```

## Important Notes

- The dataset should only be used for research purposes.
- Any use of the data must comply with the terms specified by the original data providers.

## References

- UCI Machine Learning Repository
- Druglib.com

---

