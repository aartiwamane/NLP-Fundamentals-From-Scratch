# NLP Fundamentals From Scratch

A collection of Python implementations demonstrating fundamental concepts of Natural Language Processing (NLP) and the mathematical foundations behind modern Large Language Models (LLMs).

This repository focuses on understanding how words are represented numerically and how self-attention mechanisms generate contextual representations using Python and NumPy.

## Concepts Implemented

### 1. Word Embeddings
**File:** `Embedding.py`

- Understanding numerical representations of words.
- Creating a simple embedding table.
- Mapping token IDs to their corresponding embedding vectors.
- Retrieving embeddings using NumPy array indexing.
- Understanding embedding dimensions and matrix shapes.

### 2. Scaled Dot-Product Self-Attention
**File:** `SelfAttention.py`

- Understanding Query (Q), Key (K), and Value (V) matrices.
- Calculating attention scores using dot products.
- Applying scaling using the square root of the key dimension.
- Implementing the Softmax function to calculate attention weights.
- Generating contextual representations using weighted values.
- Analyzing how words attend to other words in a sequence.

**Attention mechanism:**

Attention(Q, K, V) = Softmax(QKᵀ / √dₖ)V

Note: This is an educational implementation where Q, K, and V are simplified to use the same input embedding matrix.

## Project Structure

```text
NLP-Fundamentals-From-Scratch/
│
├── Embedding.py
├── SelfAttention.py
├── requirements.txt
└── README.md
```

## Technologies Used

- Python
- NumPy
- Natural Language Processing (NLP)
- Linear Algebra
- Deep Learning Fundamentals

## Installation and Setup

**1. Clone the repository**

```bash
git clone https://github.com/your-username/NLP-Fundamentals-From-Scratch.git
```

**2. Navigate to the project directory**

```bash
cd NLP-Fundamentals-From-Scratch
```

**3. Install dependencies**

```bash
pip install -r requirements.txt
```

**4. Execute the programs**

For word embeddings:

```bash
python Embedding.py
```

For self-attention:

```bash
python SelfAttention.py
```

## Learning Objectives

- Understand how textual data is represented numerically.
- Explore the relationship between token IDs and embedding vectors.
- Understand the mathematical operations behind self-attention.
- Learn how attention weights capture relationships between words.
- Build a foundation for understanding Transformer architectures and Large Language Models.

## Future Enhancements

- Implement word and subword tokenization.
- Explore positional encoding.
- Implement Query, Key, and Value projection matrices.
- Develop multi-head self-attention.
- Explore Transformer encoder architecture.

## Author

**Aarti Wamane**

M.Tech Computer Engineering | Machine Learning | Deep Learning | Natural Language Processing

GitHub: https://github.com/aartiwamane

---

*This repository is developed for educational purposes to understand the fundamental mathematical and computational concepts behind NLP and Transformer-based architectures.*
