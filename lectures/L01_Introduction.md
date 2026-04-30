# Lecture 1: Introduction to Generative AI

## 1. Main topics
- 6-step problem solving approach
- Predictive AI vs Generative AI
- When to use Generative AI
- End-to-end GenAI pipelines

---

## 2. Predictive AI vs Generative AI

| Point | Predictive AI | Generative AI |
|---|---|---|
| Goal | Predict label/value/class | Generate text/image/code/audio |
| Output | Usually fixed category or number | New content |
| Example | Fraud detection, demand forecast | Chatbot, summarization, image generation |
| Evaluation | Accuracy, F1, RMSE | Correctness, relevance, faithfulness, safety |
| Risk | Wrong prediction | Hallucination, unsafe output, privacy leakage |

---

## 3. GenAI pipeline

Problem definition  
→ data/knowledge source  
→ prompt/RAG/fine-tuning  
→ model response  
→ evaluation  
→ deployment  
→ monitoring

---

## 4. When to use GenAI

Use GenAI when:
- The task involves language, summarization, reasoning, generation, or conversation.
- Output can tolerate some variability.
- Human-like interaction is useful.
- Existing knowledge/documents need to be queried.

Do not use GenAI when:
- Exact deterministic answer is needed.
- Simple rule-based logic is enough.
- High-risk decision must be fully explainable.
- Data privacy cannot be handled properly.

---

## 5. Important exam points

- GenAI generates new content.
- Predictive AI predicts labels or numeric values.
- GenAI evaluation is harder than traditional ML evaluation.
- Hallucination is a key risk.
- RAG reduces hallucination by grounding answers in documents.

---

## 6. MCQ traps

- Prompting does not change model weights.
- Fine-tuning changes model weights.
- RAG retrieves external knowledge but does not necessarily train the model.
- High-quality output does not always mean factually correct output.