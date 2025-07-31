# D3: A Small Language Model for Drug-Drug Interaction Prediction

[![Paper](https://img.shields.io/badge/ScienceDirect-View%20Paper-orange)](https://www.sciencedirect.com/science/article/pii/S2666827025000416)
[![License: CC BY 4.0](https://img.shields.io/badge/license-CC--BY--4.0-brightgreen)](http://creativecommons.org/licenses/by/4.0/)

## Overview

D3 is a specialized Small Language Model (SLM) (~70M parameters) designed for accurate and efficient Drug-Drug Interaction (DDI) prediction. Despite its minimal size, D3 achieves competitive performance against leading LLMs while being 1,000× smaller and requiring significantly fewer resources.

---

## 🧠 Model on Hugging Face

| Model          | Parameters | Hugging Face Link |
|----------------|------------|-------------------|
| D3             | 70M        | [🔗 View on HF](https://huggingface.co/serag-ai/D3) |
| Qwen 2.5 (FT)  | 1.5B       | [🔗 View on HF](https://huggingface.co/serag-ai/Finetuned-DDI-Qwen) |
| Gemma 2B (FT)  | 2B         | [🔗 View on HF](https://huggingface.co/serag-ai/Finetuned-DDI-Gemma) |
| Mistral v0.3 (FT) | 7B     | [🔗 View on HF](https://huggingface.co/serag-ai/Finetuned-DDI-Mistral) |
| LLaMA 3.1 (FT) | 70B        | ⚠️ *Model not uploaded due to size constraints* |

> ℹ️ All models above were fine-tuned using the same dataset and parameter-efficient LoRA strategy.

---

## ⭐ Acknowledgement
We appreciate open source projects including: 
[Sebastian Raschka](https://github.com/rasbt), [UnSloth](https://github.com/unslothai/unsloth)
