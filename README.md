# LLM-Learning Repository
This repository contains a collection of projects and experiments developed while learning about **large language models (LLMs)**. It includes hands-on implementations using **Hugging Face Transformers**, covering topics such as:
* Prompt engineering
* In-context learning (zero-shot, one-shot, few-shot)
* Use FLAN-T5, a large language model fine-tuned with instruction-based tasks to follow natural language prompts
* Use mBART-50, a multilingual sequence-to-sequence model trained on many languages
* Translate input text
* Evaluation using BLEU score
* Proximal Policy Optimization (PPO) technique
* Direct Preference Optimization (DPO) technique
* Model pruning technique
* Knowledge distillation technique
* Retrieval-Augmented Generation (RAG) pipeline built with LangChain
* Program-Aided Language model (PAL)

---

# 📝 SummarizeDialogue.ipynb
* This file uses the **FLAN-T5 model** and **Hugging Face** to experiment with prompt engineering and in-context learning, including zero-shot, one-shot, and few-shot scenarios.

---

# 📝 DialogueToFarsi.ipynb
* This file provides a simple example of translating text from Farsi (Persian) to English using the **facebook/mbart model** from **Hugging Face Transformers**.

---

# 📝 BleuScore.ipynb
* This file compares English-to-Farsi translation quality between **facebook/mbart model** and **Google Translate**, using **BLEU score** as the evaluation metric.

---

# 📝 FineTuneWithPPO.ipynb
* In this notebook, we fine-tune the **FLAN-T5 model** to generate less toxic content using Meta AI's hate speech reward model. We employ **Proximal Policy Optimization (PPO)**, a **reinforcement learning algorithm**, to reduce the model's toxicity.

---

# 📝 FineTuneWithDPO.ipynb
* This Jupyter Notebook demonstrates how to fine-tune a language model using **Direct Preference Optimization (DPO)**. The project aligns the **Qwen/Qwen2.5-0.5B-Instruct model** to generate more desirable outputs based on a dataset of human preferences.
* **source code**: [Link](https://github.com/ShawhinT/YouTube-Blog/tree/main/LLMs)

---

# 📝 PruningLlama3_2_1b.ipynb
* This Jupyter Notebook demonstrates an advanced **model pruning technique** applied to **Meta's Llama-3.2-1B model**. The goal is to reduce the model's size and computational cost while minimizing the impact on performance.
* Please keep in mind that access to **Meta's Llama-3.2-1B model** must be requested.
* **source code**: [Link](https://github.com/peremartra/Large-Language-Model-Notebooks-Course/tree/main)

---

# 📝 KnowledgeDistillationLlama.ipynb
* The Jupyter Notebook implements **Knowledge Distillation** to improve the performance of a pruned language model. The project uses a large "teacher" model to train a smaller "student" model, transferring its knowledge and enhancing the student's capabilities.
* Please keep in mind that access to **Meta's Llama-3.2-1B model** must be requested.
* **source code**: [Link](https://github.com/peremartra/Large-Language-Model-Notebooks-Course/tree/main)

---
# 📝 RAGLangChain.ipynb
* This Jupyter Notebook demonstrates a complete **Retrieval-Augmented Generation (RAG)** pipeline built with **LangChain**. It's specifically configured to answer questions in Persian based on the content of a provided PDF document (Sample.pdf).

---

# 📝 PAL.ipynb
* This Jupyter Notebook implements a **Program-Aided Language model (PAL)** chain from scratch. It's designed to solve math and reasoning problems by generating and executing Python code.

---

