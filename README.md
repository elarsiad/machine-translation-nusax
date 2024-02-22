# NusaX Machine Translation Exploration

## Introduction
This repository contains code for exploring and analyzing machine translation tasks using the NusaX dataset. The dataset consists of translations between various languages, including Acehnese, Balinese, and Banjarese.

## Setup and Installation
To run the code in this repository, you need to install the required dependencies. You can install them using the following commands:

```bash
pip install transformers[torch]
pip install datasets
pip install accelerate
pip install evaluate
pip install scikit-learn
pip install bert-score
pip install sacrebleu
pip install sentencepiece
```

## Loading Datasets
Before performing any analysis, datasets need to be loaded. This repository provides functionality to load the NusaX dataset using the Hugging Face datasets library.

## Exploratory Data Analysis (EDA)
The repository includes exploratory data analysis to gain insights into the datasets. This involves:
- Converting datasets into Pandas DataFrames
- Merging split datasets for easier analysis
- Analyzing text lengths, common words, and bigrams
- Visualizing distributions and word clouds

## Model Training and Evaluation
The code facilitates training and evaluating machine translation models using the T5 model architecture. This involves:
- Setting up translation tasks
- Preprocessing datasets for model training
- Training the model using Seq2SeqTrainer
- Evaluating model performance using various metrics such as BLEU, METEOR, BERTScore, and BLEURT

## Predictions and Evaluation
The repository allows making predictions on the test dataset and evaluating model performance. This involves:
- Predicting translations for test dataset
- Evaluating translations using accuracy, BLEU, METEOR, BERTScore, and BLEURT
- Generating Pandas DataFrame for analysis

## Usage
To utilize the functionalities provided in this repository, follow these steps:
1. Install dependencies as mentioned in the "Setup and Installation" section.
2. Load the datasets using the provided code.
3. Perform exploratory data analysis to understand the datasets better.
4. Train machine translation models using the T5 architecture.
5. Evaluate model performance on test datasets.
6. Analyze predictions and evaluation metrics.
