# KAIM-W1
A repo for Kifya Ai Mastery program Week 1

## Overview

This project focuses on the detailed analysis of a large corpus of financial news data to discover correlations between news sentiment and stock market movements. By integrating qualitative and quantitative data, this analysis aims to enhance stock market predictions and provide insights into how financial news impacts market behavior.

## Analyses Performed

- **Descriptive Statistics**: Analysis of headline lengths, article counts per publisher, and publication date trends.
- **Sentiment Analysis**: Classification of headlines into `negative`, `positive`, and `neutral`, with visualization of sentiment distribution.
- **Topic Modeling**: Extraction of common topics and key phrases using TF-IDF vectorization and Latent Dirichlet Allocation (LDA).
- **Time Series Analysis**: Examination of publication frequency over time and identification of key market events.
- **Publisher Analysis**: Evaluation of publisher contributions and differences in the types of news they report.

## Project Structure

- `data/`: Directory containing the dataset.
- `notebooks/`: Jupyter notebooks containing the analysis.

## How to Run

1. Clone the repository:
   ```bash
   https://github.com/BekLG/KAIM-W1.git

2. Install the required dependencies::
   ```bash
   pip install -r requirements.txt

3. Open the Jupyter notebook and run the cells to see the analysis


## Dependencies

- pandas
- matplotlib.pyplot
- seaborn
- nltk
- TextBlob
- CountVectorizer (from sklearn)
- LatentDirichletAllocation (from sklearn)
- TfidfVectorizer (from sklearn)
- pynance
- TA-Lib

