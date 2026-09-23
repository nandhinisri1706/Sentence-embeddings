# Embedding Models – From Text to Meaningful Vector Representations

## Overview

This project demonstrates how **text can be converted into meaningful numerical vector representations using an embedding model**.

The project uses the **Sentence Transformers** library with the `all-MiniLM-L6-v2` model to convert sentences into **384-dimensional embedding vectors**.

These embeddings are then compared using **Cosine Similarity** to identify the semantic similarity between sentences.

---

## How It Works

```text
Input Text
    ↓
Sentence Transformer Model
    ↓
384-Dimensional Embedding
    ↓
Cosine Similarity
    ↓
Similarity Score
    ↓
Semantic Result
```

---

## Technologies Used

* Python
* Sentence Transformers
* Scikit-learn
* ReportLab
* `all-MiniLM-L6-v2`

---

## Model Used

### all-MiniLM-L6-v2

The `all-MiniLM-L6-v2` model converts text into fixed-size numerical vectors.

**Embedding Dimension:** 384

Example:

```text
"I enjoy coding."
        ↓
[0.0342, -0.0187, 0.0521, ...]
        ↓
384-dimensional vector
```

---

## Features

* Converts text into embeddings
* Generates 384-dimensional vector representations
* Compares the semantic meaning of sentences
* Calculates Cosine Similarity
* Displays similarity scores
* Generates an output PDF containing the results

---

## Example

### Input

```text
Sentence 1:
I enjoy coding.

Sentence 2:
I like programming.
```

### Process

Both sentences are converted into numerical embeddings using the Transformer model.

The resulting vectors are compared using Cosine Similarity.

### Output

```text
Embedding Dimension: 384

Sentence 1: I enjoy coding.
Sentence 2: I like programming.

Similarity Score: 0.xxxx
```

A higher similarity score indicates that the two sentences have more similar semantic meaning.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/Embedding-Models-From-Text-to-Meaningful-Vector-Representations.git
```

Navigate to the project folder:

```bash
cd Embedding-Models-From-Text-to-Meaningful-Vector-Representations
```

Install the required libraries:

```bash
pip install sentence-transformers scikit-learn reportlab
```

---

## Run the Project

Run the Python program:

```bash
python app.py
```

The program generates the sentence embeddings, calculates their similarity, and produces the output PDF.

---

## Project Structure

```text
Embedding-Models-From-Text-to-Meaningful-Vector-Representations/
│
├── app.py
├── README.md
├── output.pdf
└── requirements.txt
```

---

## Requirements

The project dependencies are:

```text
sentence-transformers
scikit-learn
reportlab
```

You can also install them using:

```bash
pip install -r requirements.txt
```

---

## Applications

Text embeddings can be used in many Natural Language Processing applications, including:

* Semantic Search
* Document Similarity
* Text Classification
* Recommendation Systems
* Question Answering
* Information Retrieval
* Duplicate Text Detection
* Chatbots

---

## Key Concepts

### Text Embedding

Text embedding converts text into numerical vectors that capture the semantic meaning of the text.

### Transformer

Transformers are deep learning models that are highly effective for understanding relationships and context within text.

### Cosine Similarity

Cosine Similarity measures the similarity between two vectors based on the angle between them.

```text
Higher similarity → More similar meaning

Lower similarity → Less similar meaning
```

---

## Output

The project generates an `output.pdf` file containing:

* Input sentences
* Embedding model information
* Embedding dimension
* Vector representations
* Cosine similarity scores
* Semantic similarity results


B.Sc. Computer Science with Artificial Intelligence
