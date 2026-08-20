# Tesla Employee Sentiment Analysis

## Overview

This project analyses employee-related discussions about Tesla from YouTube comments to identify overall sentiment, recurring themes, and key workforce concerns.

Using Natural Language Processing (NLP), the project processes large-scale unstructured text data and transforms it into meaningful insights through sentiment analysis, topic modelling, and data visualization.

## Objectives

- Collect employee-related YouTube comments using the YouTube Data API v3
- Clean and preprocess unstructured text data
- Analyse sentiment using multiple sentiment analysis approaches
- Identify recurring themes using topic modelling
- Explore patterns related to employee experiences and workplace discussions
- Communicate findings through visualizations and interactive analysis

## Dataset

The project collected and analysed **9,000+ YouTube comments** related to Tesla employee experiences and workplace discussions.

Data was collected using the **YouTube Data API v3** through Google Cloud.

Key processing steps included:

- Data extraction from YouTube
- Text cleaning and preprocessing
- Duplicate and missing-value handling
- Tokenization
- Stopword removal
- Data validation

## Methodology

### 1. Data Collection

YouTube comments were collected programmatically using the YouTube Data API v3.

### 2. Data Preprocessing

Raw comments were cleaned and prepared for analysis by:

- Removing URLs and special characters
- Converting text to lowercase
- Tokenizing text
- Removing stopwords
- Handling missing and duplicate records

### 3. Sentiment Analysis

Sentiment was analysed using:

- **VADER**
- **TextBlob**

Comments were classified to identify positive, negative, and neutral sentiment patterns.

### 4. Topic Modelling

**Latent Dirichlet Allocation (LDA)** was applied to identify recurring themes and hidden topics within employee discussions.

The analysis surfaced themes related to areas such as:

- Workload
- Compensation
- Management
- Workplace culture

### 5. Visualization

Results were communicated through:

- Sentiment distribution charts
- Word clouds
- Topic visualizations
- Interactive analysis using **pyLDAvis**

## Technologies Used

- Python
- Pandas
- NumPy
- YouTube Data API v3
- Google Cloud
- NLTK
- VADER
- TextBlob
- Gensim
- pyLDAvis
- Matplotlib

## Key Insights

The analysis identified recurring patterns in employee-related discussions, including themes surrounding:

- Workplace culture
- Workload
- Compensation
- Management experiences

These findings demonstrate how unstructured social media data can be transformed into insights that support workforce and organisational analysis.
