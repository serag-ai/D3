# D3: A Small Language Model for Drug-Drug Interaction Prediction

[![Paper](https://img.shields.io/badge/ScienceDirect-View%20Paper-orange)](https://www.sciencedirect.com/science/article/pii/S2666827025000416)
[![License: CC BY 4.0](https://img.shields.io/badge/license-CC--BY--4.0-brightgreen)](http://creativecommons.org/licenses/by/4.0/)

## Overview

**D3** is a compact Small Language Model (SLM) (~70M parameters) developed specifically for **Drug-Drug Interaction (DDI)** prediction. Despite its small size, D3 achieves performance on par with leading Large Language Models (LLMs) such as LLaMA 3.1 (70B), Mistral v0.3, Gemma 2B, and Qwen 2.5B—while being 1000× smaller and significantly more resource-efficient.

---

## 🧠 Model Checkpoints on Hugging Face

| Model          | Parameters | Hugging Face Link |
|----------------|------------|-------------------|
| D3             | 70M        | [🔗 View on HF](https://huggingface.co/your-username/D3) |
| Qwen 2.5 (FT)  | 1.5B       | [🔗 View on HF](https://huggingface.co/your-username/Qwen2.5-DDI) |
| Gemma 2B (FT)  | 2B         | [🔗 View on HF](https://huggingface.co/your-username/Gemma2-DDI) |
| Mistral v0.3 (FT) | 7B     | [🔗 View on HF](https://huggingface.co/your-username/Mistral-DDI) |
| LLaMA 3.1 (FT) | 70B        | [🔗 View on HF](https://huggingface.co/your-username/LLaMA3.1-DDI) |

> ℹ️ All models above were fine-tuned using the same dataset and parameter-efficient LoRA strategy.

---

## 💚 Acknowledgement
We appreciate open source projects including: 
[Sebastian Raschka](https://github.com/rasbt), [UnSloth](https://github.com/unslothai/unsloth)
