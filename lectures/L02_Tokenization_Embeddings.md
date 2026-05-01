# L02: Tokenization and Embeddings

## 1. NLP tasks

Natural Language Understanding:
- Topic modelling
- Sentiment analysis
- Content filtering
- Named entity recognition
- Information retrieval

Natural Language Generation:
- Language modelling
- Translation
- Summarization
- Question answering

## 2. Tokenization

Tokenization is the process of breaking data into smaller units called tokens.

For text, tokens may be:
- Words
- Subwords
- Characters

For images, tokens may be:
- Pixels
- Patches
- Processed patches

For audio, tokens/features may be:
- Acoustic feature vectors
- Log-mel spectrum vectors

## 3. BPE

Byte Pair Encoding starts with small units and repeatedly merges frequent pairs until the desired vocabulary size is reached.

Advantages:
- Handles out-of-vocabulary words
- Balances words and subwords
- Captures prefixes and suffixes

Limitations:
- Can produce unintuitive splits
- Vocabulary size affects tokenization quality

## 4. Vocabulary indexing

After tokenization:
Token → token ID → one-hot vector → embedding vector

## 5. Word embeddings

One-hot vectors treat all words as independent.
Embeddings represent words in a geometric space where semantic similarity can be captured.

Example:
- king and queen should be related
- walking and walked should be related
- country and capital should be related

## 6. Embedding layer

An embedding layer maps token IDs to dense vectors.
The embedding matrix is learned using backpropagation.
Embedding dimension is a hyperparameter.

## 7. Exam traps
- Tokenization is not the same as embedding.
- Token ID is not the same as embedding vector.
- One-hot vectors are sparse and high-dimensional.
- Embeddings are dense and learned.
- Vocabulary size and embedding dimension are hyperparameters.
