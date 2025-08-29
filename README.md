# LLM-Learning Repository
This repository contains a collection of projects and experiments developed while learning about **large language models (LLMs)**. It includes hands-on implementations using **Hugging Face Transformers**, covering topics such as:
* Prompt engineering
* In-context learning (zero-shot, one-shot, few-shot)
* Use FLAN-T5, a large language model fine-tuned with instruction-based tasks to follow natural language prompts
* Use mBART-50, a multilingual sequence-to-sequence model trained on many languages
* Translate input text
* Evaluation using BLEU score
* Parameter-Efficient Fine-Tuning (PEFT) technique
* Low-Rank Adaptation (LoRA)
* Proximal Policy Optimization (PPO) technique
* Direct Preference Optimization (DPO) technique
* Group Relative Policy Optimization (GRPO) technique
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

# 📝 FineTunePEFT_DialogueSummarization.ipynb
* In this notebook, we fine-tune the **FLAN-T5 model** from Hugging Face for enhanced dialogue summarization. To improve the inferences, we explore a full fine-tuning approach and evaluate the results with **ROUGE metrics**. Then, we perform **Parameter-Efficient Fine-Tuning (PEFT)** with **LoRA (Low-Rank Adaptation)**, evaluate the resulting model, and observe that the benefits of PEFT outweigh the slightly lower performance metrics.

---

# 📝 FineTuneWithPPO.ipynb
* In this notebook, we fine-tune the **FLAN-T5 model** to generate less toxic content using Meta AI's hate speech reward model. We employ **Proximal Policy Optimization (PPO)**, a **reinforcement learning algorithm**, to reduce the model's toxicity.

---

# 📝 FineTuneWithDPO.ipynb
* This Jupyter Notebook demonstrates how to fine-tune a language model using **Direct Preference Optimization (DPO)**. The project aligns the **Qwen2.5 model** to generate more desirable outputs based on a dataset of human preferences.
* **source code**: [Link](https://github.com/ShawhinT/YouTube-Blog/tree/main/LLMs)

---

# 📝 FineTuneWithDPO_Unsloth.ipynb
* This Jupyter Notebook demonstrates how to fine-tune a language model using **Direct Preference Optimization (DPO)**. The project aligns the **Qwen2.5 model** to generate more desirable outputs based on a dataset of human preferences. The project leverages the **Unsloth library** for highly efficient training.

---

# 📝 FineTuneWithDPOPhi3.ipynb
* This Jupyter Notebook is for fine-tuning the **microsoft/Phi-3-mini-4k-instruct model** using **Direct Preference Optimization (DPO)**. The project aligns the model with human preferences using the argilla/distilabel-capybara-dpo-7k-binarized dataset.
* **source code**: [Link](https://github.com/peremartra/Large-Language-Model-Notebooks-Course)

---

# 📝 FineTuneWithGRPO_Unsloth.ipynb
* This Jupyter Notebook contains fine-tuning the **Qwen2.5 model** using **Group Relative Policy Optimization (GRPO)** as a **reinforcement learning–based fine-tuning method** for mathematical reasoning tasks. The project leverages the **Unsloth library** for highly efficient training.
* **source code**: [Link](https://github.com/unslothai/notebooks)

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

