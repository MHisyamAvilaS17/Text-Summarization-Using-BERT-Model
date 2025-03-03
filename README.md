# Text Summarization on Liputan6 News Dataset

## Overview

This project implements a Text Summarization model using **BERT** with an **abstractive summarization** approach. The goal is to automatically summarize news articles from Liputan6, one of Indonesia’s leading news outlets. By summarizing the articles, we aim to reduce information overload and make the content more accessible to readers. The model leverages BERT for abstractive summarization to generate concise yet informative summaries of the articles.

Liputan6 is one of Indonesia's most prominent news outlets, offering a diverse array of news content. With the rise of digital content, the volume of information has grown, which often overwhelms readers. Text Summarization helps alleviate this issue by condensing large articles into shorter, easy-to-read summaries while maintaining the core information.

For this project, we utilize **BERT** (Bidirectional Encoder Representations from Transformers) in an **abstractive summarization** approach. The model generates new sentences rather than simply extracting sentences from the original text, creating summaries that are both concise and informative.

### Why BERT for Abstractive Summarization?
- BERT excels at understanding the context and relationships between words, which allows it to generate summaries that accurately reflect the key points of the original text.
- Abstractive summarization can produce more natural, human-like summaries as it rewrites the text rather than simply selecting existing sentences.
  
The model’s performance will be evaluated based on readability and accuracy to ensure it meets quality standards and improves the user experience for Liputan6 readers.

## Dataset

The dataset used in this project contains news articles from Liputan6, which is available on Google Drive. Please download the dataset from the following link and extract it to your working directory:

[Download Liputan6 News Dataset](https://drive.google.com/drive/u/0/folders/1rm7prqVbM94afxSjeeudC7YLYZ2ERXJI)

## Requirements

Before running the project, ensure that all the required dependencies are installed. You can install them using `requirements.txt`.
