This repository hosts three powerful Sinhala language models developed by **Team TripleBits** for the **ICIIT Shared Task 2025**. These models are based on **LLaMA 3.2 1B** and **Gemma 2B** architectures, and trained with **Continual Pretraining (CPT)** and **Q&A Fine-Tuning** on diverse Sinhala corpora.

---

## 🔍 Available Models

### 1. 🦙 Sinhala-LLaMA 3.2 1B (CPT)
- **Base Model**: `meta-llama/Llama-3.2-1B`
- **Checkpoint**: [`iCIIT/TripleBits-Sinhala-Llama-3.2-1B-CP`](https://huggingface.co/iCIIT/TripleBits-Sinhala-Llama-3.2-1B-CP)
- **Training Objective**: Continual Pretraining (CPT) on Sinhala Wikipedia
- **Model Size**: 1 Billion parameters

### 2. 💎 Sinhala-Gemma 2B (CPT)
- **Base Model**: `google/gemma-2-2b`
- **Checkpoint**: [`iCIIT/TripleBits-Sinhala-Gemma-2-2b-CP`](https://huggingface.co/iCIIT/TripleBits-Sinhala-Gemma-2-2b-CP)
- **Training Objective**: CPT on Sinhala Wikipedia
- **Model Size**: 2 Billion parameters

### 3. 🤖 Sinhala-Gemma 2B (QnA Fine-Tuned)
- **Base Model**: `google/gemma-2-2b`
- **Checkpoint**: [`iCIIT/TripleBits-Sinhala-Gemma-2-2b-FT`](https://huggingface.co/iCIIT/TripleBits-Sinhala-Gemma-2-2b-FT)
- **Training Objective**:
  - CPT on Sinhala Wikipedia
  - Fine-tuned for Question Answering using instruction-tuned Sinhala data
- **Model Size**: 2 Billion parameters

---
