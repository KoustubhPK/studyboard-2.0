# 🚀 StudyBoard 2.0: Advanced AI & Engineering Mastery

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Made with Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?logo=jupyter)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VSCode-0078d7?logo=visual-studio-code&logoColor=white)

Welcome to my central repository for mastering Natural Language Processing (NLP), Deep Learning, Generative AI, Agentic Workflows, and production-grade LLMOps. This project is structured chronologically by module to maintain clean, production-level code isolation and dependency management.

---

## 🛠️ Repository Architecture & Workspace Standards
Every core technical directory utilizes strict modular isolation rules to keep personal study separated from public-facing code:
*   `exercises/` — **[🟢 Public]** Contains clean experimental scripts, Jupyter Notebooks (`.ipynb`), concept verification tests, and optimized practice implementations visible on GitHub.
*   `src/` — **[🔴 Private / Git-Ignored]** Contains internal study notes, raw tracking material, and direct training assignments. This directory is strictly isolated locally to emulate enterprise privacy compliance.

---

## 🗺️ Master Curriculum & Progress Tracker

### 📦 01. NLP & Sequential Models
*Isolated Virtual Environment: `env_nlp` (CPU Optimized)* | 🐍 [Environment Dependencies](01_nlp_and_sequential/requirements.txt)

- [x] **Module 1: Introduction to the Program**
  - [x] Core Concepts: NLP, GenAI, and Agentic AI landscapes.
  - [x] Deliverables: 📄 [Introduction](01_nlp_and_sequential/exercises/01-introduction.ipynb)

- [x] **Module 2: NLP Fundamentals**
  - [x] Core Concepts: Tokenization, Text Preprocessing, Regex, One-Hot Encoding, Bag of Words, N-Grams, TF-IDF, Word2Vec, GloVe embeddings.
  - [x] Deliverables:
  📄 [Tokenization](01_nlp_and_sequential/exercises/02-tokenization.ipynb)
  📄 [Text Preprocessing](01_nlp_and_sequential/exercises/03-text-preprocessing.ipynb)
  📄 [Regex](01_nlp_and_sequential/exercises/04-regex.ipynb)
  📄 [Text Representation _(One-Hot, BoW, N-Grams, TF-IDF)_](01_nlp_and_sequential/exercises/05-text-representation.ipynb)
  📄 [Word2Vec](01_nlp_and_sequential/exercises/06_word2vec.ipynb)

---

### 🧠 02. Deep Learning Core & Transformer Mechanics
*Isolated Virtual Environment: `env_dl` (GPU / PyTorch Accelerated)* | 🐍 [Environment Dependencies](02_deep_learning_core/requirements.txt)
- [x] **Module 3: Deep Learning Fundamentals**
  - [x] Core Concepts: Artificial Neural Networks (ANNs), Gradient Descent, Chain Rule, Loss and Activation Functions, Vanishing/Exploding Gradients.
  - [x] Deliverables:
  📄 [Neural Networks: Fundamentals, Training & Optimization](02_deep_learning_core/exercises/07_neural_network.ipynb)
  📄 [ANN Implementation using TensorFlow/Keras](02_deep_learning_core/exercises/08_ann_implementation.ipynb)

- [x] **Module 4: Sequential Models for NLP**
  - [x] Core Concepts: Recurrent Neural Networks (RNNs), LSTMs, GRUs, Bidirectional architectures.
  - [x] Deliverables:
  📄 [Recurrent Neural Networks (RNNs)](02_deep_learning_core/exercises/09_rnn.ipynb)
  📄 [RNN Implementation using TensorFlow/Keras](02_deep_learning_core/exercises/10_rnn_implementation.ipynb)
  📄 [Long Short-Term Memory (LSTM) - Notes & Implementation](02_deep_learning_core/exercises/11_lstm.ipynb)
  📄 [Gated Recurrent Unit (GRU) & Bidirectional RNN](02_deep_learning_core/exercises/12_gru_&_bidirectional.ipynb)

- [x] **Module 5: Transformer Architecture & Variants**
  - [x] Core Concepts: Encoder-Decoder Architecture, Positional Encoding, BERT, RoBERTa, GPT family, T5, BART.
  - [x] Deliverables:
  📄 [Encoder–Decoder Architecture](02_deep_learning_core/exercises/13_encoder_decoder.ipynb)
  📄 [Attention Mechanism](02_deep_learning_core/exercises/14_attention_mechanism.ipynb)
  📄 [Transformer](02_deep_learning_core/exercises/15_transformer.ipynb)
  📄 [Positional Encoding](02_deep_learning_core/exercises/16_positional_encoding.ipynb)
  📄 [Hugging Face](02_deep_learning_core/exercises/17_huggingface.ipynb)
  📄 [BERT](02_deep_learning_core/exercises/18_bert.ipynb)
  📄 [Decoding Strategies for Language Models](02_deep_learning_core/exercises/19_decoding_strategies.ipynb)

---

### 🤖 03. Generative AI & Advanced RAG Systems
*Isolated Virtual Environment: `env_genai` (Vector Databases & LLM Orchestration)* | 🐍 [Environment Dependencies](03_genai/requirements.txt)
- [ ] **Module 6: Pretrained Models & LLMs**
  - [ ] Core Concepts: LLM Landscape, evaluation scales (Perplexity, BLEU, ROUGE).
  - [x] Deliverables:
  📄 [Large Language Models (LLM)](03_genai/exercises/22_llm.ipynb)

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. You are free to use, modify, and distribute this code for personal study or production deployment.

---

## 🤝 Thank You & Connect!

Thank you for visiting my study board repository! This continuous iteration loop is built to hone my fundamentals and scale up production architectures. 

If you are an interviewer, recruiter, or fellow engineer looking to discuss system design, production LLM pipelines, or agentic ecosystems, feel free to reach out or drop a star ⭐ on this repository!

*   **GitHub**: [@KoustubhPK](https://github.com/KoustubhPK/)
*   **Portfolio**: [https://koustubhpk.pythonanywhere.com/](https://koustubhpk.pythonanywhere.com/)