# Healthcare-Q-A-Chatbot-Using-Sentence-Embeddings-and-Gemini

![Sample Output](https://github.com/royadeh/Healthcare-Q-A-Chatbot-Using-Sentence-Embeddings-and-Gemini/blob/main/Q%26A.png)

## Overview

This project is a Patient Education Chatbot that uses sentence embeddings to find the most relevant healthcare questions and answers from a dataset, then uses the Gemini AI model to generate friendly, easy-to-understand responses with emojis.

## Features

- Finds top relevant questions and answers using sentence embeddings and cosine similarity.
- Generates concise, emoji-enhanced bullet point summaries with Gemini AI.
- Interactive chat interface allowing continuous questions and answers.
- Lightweight — processes top 100 dataset entries for fast responses.

## How It Works

1. The user's question is converted into an embedding.
2. Cosine similarity scores are computed against pre-calculated embeddings of the dataset.
3. Top matching Q&A pairs are selected.
4. Gemini AI model generates a friendly summary using these top resources.
5. The chatbot interacts in a loop until the user types `'exit'`.


## Requirements

- Python 3.x
- sentence-transformers
- PyTorch
- OpenAI / Gemini API access


## Usage

1. Clone the repository:

```bash
git clone https://github.com/royadeh/Healthcare-Q-A-Chatbot-Using-Sentence-Embeddings-and-Gemini.git
cd Healthcare-Q-A-Chatbot-Using-Sentence-Embeddings-and-Gemini
