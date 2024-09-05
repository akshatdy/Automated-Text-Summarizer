# Automated Text Summarizer

## Overview

This project develops a hybrid text summarization model that handles both long and short texts using a combination of extractive and abstractive techniques. The system is designed to generate concise summaries from legal judgments and customer reviews.

## Folder Structure

- **Dataset**:
  - `amazon_food_review`: Dataset for short text reviews.
  - `legal_judgments`: Dataset for legal judgments.

- **Code**:
  - `Project_legal`: Code for generating summaries from legal texts.
  - `Project_review`: Code for generating summaries from short texts.
  - `Project_testing_data`: Code for creating testing datasets for legal texts.
  - `Project_training_data`: Code for creating training datasets for short texts.

## Features

- **Long Text Summarization**: Efficiently generates summaries for extensive legal documents.
- **Short Text Summarization**: Provides brief summaries for customer reviews.
- **Hybrid Approach**: Utilizes both extractive and abstractive summarization techniques.

## Dataset

- **`amazon_food_review`**: Contains customer reviews for training and evaluation of short text summarization.
- **`legal_judgments`**: Contains Supreme Court of India judgments for training and evaluation of legal text summarization.

## Objectives

- Develop a summarization system that adapts to varying text lengths.
- Generate accurate and concise summaries for legal documents and short reviews.
- Create and utilize datasets for training and evaluation.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/akshatdy/Automated-Text-Summarizer.git

2. Upload the datasets to the appropriate directories:
   - Place the `amazon_food_review` dataset in the `Dataset/amazon_food_review` directory.
   - Place the `legal_judgments` dataset in the `Dataset/legal_judgments` directory.


## Usage

1. **Start Jupyter Notebook**:

   ```bash
   jupyter notebook

2. **Open and Run Jupyter Notebooks**:
   - Navigate to the `.ipy` files in your browser and open them.
   - Update file paths in the notebooks to point to the uploaded datasets:
   - Execute the cells to run the summarization models.

   
## Conclusion

This project automates text summarization for both long (legal texts) and short (reviews) documents using a hybrid approach, providing efficient summarization across different domains.