# Comparative Analysis of Sentiment and Emotion Classification with PySpark

## Project Overview

This repository contains the full source code for the research paper, **"Comparative Analysis of Sentiment and Emotion Classification Using TF-IDF and BERT Embeddings on Big Data with PySpark."** The project investigates the trade-offs between traditional and modern NLP techniques for large-scale text analysis.

We compare the performance and scalability of two distinct approaches on two benchmark datasets:
1.  A traditional, scalable **TF-IDF (Term Frequency-Inverse Document Frequency)** approach with a Logistic Regression classifier.
2.  A modern, high-accuracy approach using **DistilBERT embeddings** as features for a Logistic Regression classifier.

The entire workflow is implemented on a distributed computing framework, **Apache Spark**, using the **PySpark** library, which demonstrates the feasibility of applying sophisticated deep learning models to big data problems.

## Key Findings

-   **Accuracy:** The DistilBERT-based model consistently and significantly outperforms the TF-IDF baseline on both sentiment and emotion classification tasks.
-   **Scalability:** The TF-IDF model is significantly faster and more resource-efficient, making it ideal for real-time applications. The DistilBERT model, while more accurate, is computationally intensive.
-   **Methodology:** The project provides a practical blueprint for integrating powerful transformer models with a distributed big data framework.

## Repository Structure

-   `sentiment_analysis.ipynb`: The main Jupyter Notebook containing all the code for data preprocessing, model training, evaluation, and visualization.
-   `README.md`: This file, providing an overview of the project.


### Datasets
The project uses two public datasets. The notebook will automatically download them, but here are the direct links for reference:

-  Sentiment140: http://cs.stanford.edu/people/alecmgo/trainingandtestdata.zip
-  TweetEval (Emotion Subtask): https://huggingface.co/datasets/cardiffnlp/tweet_eval

### Contact
-  Author: Ibrahim O. I. Kaware
-  Email: ibrahimokaware@gmail.com

This project is supervised by Dr. Rebhi S. Baraka and is a requirement of the course Big Data (ICTS 6339), Faculty of Information Technology, The Islamic University of Gaza (IUG).
