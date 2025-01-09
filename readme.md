# 🧬 D3: A Small Language Model for Drug-Drug Interaction Prediction

🚧 **Under Development** 🚧  
This repository is a work in progress and is not yet complete. Features and documentation are subject to change.

Welcome to the **D3 Project** repository! In this study, we developed **D3**, a Small Language Model (SLM) designed to predict **Drug-Drug Interactions (DDI)**. While larger models often hog the spotlight, our focus here is to strike a balance between **high performance** and **resource efficiency** — and to show that **smaller can be just as powerful**.

## 🌟 Overview

**DDI prediction** plays a critical role in healthcare, especially as drug combinations become more common in treatment plans. Traditional methods for identifying DDIs can be **labor-intensive** and **error-prone**. To solve this, we pre-trained **D3**, a nimble small language model, using data compiled from **DrugBank** and compared it against state-of-the-art, finetuned **Large Language Models (LLMs)**, including:

- **Qwen 2.5**
- **Gemma 2**
- **Mistral v0.3**
- **LLaMA 3.1** 🦙

Despite being **1,000 times smaller** than LLaMA 3, **D3** managed to hold its ground by delivering **competitive results** in DDI prediction, confirmed through both **metrics** and **expert evaluations**. 📊👩‍⚕️👨‍⚕️

## 📁 Project Structure
- `src/`: Source code for the model implementation and utilities
- `d3_pretraining_finetuning.ipynb`: Jupyter Notebook used for pretraining and fine-tuning the SLM D3
- `llm_finetuning.ipynb`: Jupyter Notebook used for finetuning the D3 model
- `requirements.txt`: Python dependencies for this project


## 💚 Acknowledgement
We appreciate open source projects including: 
[Sebastian Raschka](https://github.com/rasbt), [UnSloth](https://github.com/unslothai/unsloth)


