# Deep Learning / GenAI Final Revision Master

## Scoring structure

| Component | Weight |
|---|---:|
| Midterm MCQ | 5% |
| Project | 30% |
| Final MCQ | 65% |

---

# High-priority final topics

## 1. GenAI basics
- Predictive AI vs Generative AI
- GenAI pipeline
- When to use GenAI
- Hallucination
- RAG

## 2. Deep Neural Networks
- Neuron
- Activation
- Loss
- Backpropagation
- Optimizer
- Overfitting

## 3. Transformers
- Tokenization
- Embeddings
- Query, Key, Value
- Self-attention
- Multi-head attention
- Positional encoding

## 4. Decoding
- Greedy decoding
- Beam search
- Temperature
- Top-k
- Top-p

## 5. Post-training
- Pretraining
- SFT
- RLHF
- RLAIF
- Distillation

## 6. Agents
- Tool calling
- Planning
- Agent workflow
- Context engineering
- MCP
- A2A

## 7. Evals and LLMOps
- Correctness
- Faithfulness
- Relevance
- Safety
- Latency
- Cost
- Deployment
- Monitoring

# Week 1 Final Revision: GenAI Basics

## Predictive AI vs Generative AI

Predictive AI predicts labels, values, or decisions from input data.

Examples:
- Spam detection
- Fraud detection
- Sales forecasting
- House price prediction

Generative AI creates new content.

Examples:
- Text generation
- Code generation
- Image generation
- Summarization
- Chatbots

Key difference:
Predictive AI predicts; Generative AI generates.

---

## GenAI Pipeline

Problem definition  
→ data/knowledge source  
→ preprocessing  
→ prompt/RAG/fine-tuning  
→ model inference  
→ evaluation  
→ deployment  
→ monitoring

Important:
A GenAI system is not only an LLM call. Evaluation, deployment, and monitoring are part of the complete system.

---

## RAG

RAG = Retrieval-Augmented Generation.

Flow:
User query  
→ retrieve relevant document chunks  
→ give retrieved context to LLM  
→ generate grounded answer

RAG is useful for:
- private company data
- frequently changing data
- reducing hallucination
- source-grounded answers

RAG does not update model weights.

---

## Hallucination

Hallucination means the model gives a fluent but incorrect, fabricated, or unsupported answer.

Causes:
- missing context
- poor retrieval
- outdated knowledge
- ambiguous question
- high randomness

Ways to reduce:
- RAG
- source citation
- better prompting
- low temperature
- evaluation
- human review
