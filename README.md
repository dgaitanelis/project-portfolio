## 🔍 Project Portfolio – Dimitris Gaitanelis

Welcome! This public repository offers an overview of selected private projects I've developed across machine learning, NLP, full-stack apps, and multi-agent systems. While the source code remains private (due to ongoing development or sensitive components), I'm happy to walk you through any of these upon request.

---

## 1. Hacker News Upvote Predictor 🧠 *(Private)*  
**Tech:** PyTorch, FastAPI, Streamlit, Docker  
**Description:** A multi-model deep learning system that predicts Hacker News upvotes based on post title and timestamp.  
**Highlights:**
- Late fusion of temporal, textual, and embedding-based features
- Custom CBOW model for title embedding
- Batch prediction via CLI + interactive Streamlit UI
- Dockerised deployment
**Demo:** Available upon request

---

## 2. Two-Tower Semantic Search Engine 🔎 *(Private)*  
**Tech:** PyTorch, FastAPI, ChromaDB, Streamlit, Weights & Biases  
**Description:** Neural search system using MS MARCO data and a Two-Tower architecture trained via triplet loss.  
**Highlights:**
- Custom tokenizers and CBOW embedding layer
- Cosine similarity-based ranking
- Persistent vector search with ChromaDB
- UI + API interface for querying  
**Demo:** Walkthrough available upon request

---

## 3. MNIST Transformer: Vision-to-Sequence Model for Digit Grid images 🔢 *(Private)*  
**Tech:** PyTorch  
**Description:** A transformer-based encoder-decoder model developed from scratch to decode digit sequences from composite MNIST grids.  
**Highlights:**
- Manual implementation of attention mechanisms
- Autoregressive decoding
- Patch embedding and visualization tools
- Tracked experiments using wandb  
**Demo:** Visuals available on request

---

## 4. MNIST Transformer Classifier with W&B Integration ✍️📈 (Private)

**Tech:** PyTorch, Streamlit, FastAPI, Weights & Biases  
**Description:** A full ML workflow example featuring a patch-based Vision Transformer trained on MNIST with Bayesian hyperparameter sweeps and real-time performance tracking.  

**Highlights:**
- Transformer encoder with patch embedding and multi-head attention  
- W&B sweep for architecture search with automatic config selection  
- Streamlit app for interactive inference and ground-truth feedback  
- Live logging of confidence, latency, and per-class accuracy to W&B  
- FastAPI server for RESTful predictions  
- Post-hoc analysis tools for visualizing misclassifications and confidence distributions

⚙️ Designed to demonstrate how W&B can support lightweight production-style monitoring and feedback loops  

**Demo:** Streamlit/W&B walkthrough available upon request

---

## 5. DinoBot: Fine-Tuning TinyLLaMA with LoRA 🦖 *(Private)*  
**Tech:** TinyLLaMA, LoRA, PEFT, Gradio  
**Description:** Fine-tuned TinyLLaMA into a fun "dinosaur conspiracy" chatbot using handcrafted training data.  
**Highlights:**
- 4-bit quantized LoRA training
- Conda setup script for quick environment setup
- Inference via CLI and Gradio interface  
**Demo:** Gradio demo available upon request

---

## 6. LangGraph Multi-Agent Architectures 🤖 *(Private – Workshop Repo)*  
**Tech:** LangGraph, Python, OpenAI API  
**Description:** A hands-on workshop project exploring 6 core multi-agent system patterns using LangGraph.  
**Patterns Covered:**
1. Sequential Workflow  
2. Conditional Routing  
3. Parallel Processing  
4. Supervisor Agents  
5. Evaluator-Optimiser  
6. Orchestrator-Worker  
**Workshop Repo:** Based on [Tandem Creative Dev](https://github.com/TandemCreativeDev)

---

## 🗂️ How to Request Access or Demos
If you would like to see any of these projects in action:
- 📩 Reach out via [LinkedIn](https://www.linkedin.com/in/dimitris-gaitanelis/) or email
- 🔐 I can provide walkthroughs, architecture diagrams, or live demos depending on your interest

---

## 🙌 About Me
I'm Dimitris Gaitanelis – an engineer focused on building intelligent systems that blend ML/NLP with production-ready applications. Whether it's search, prediction, language models, or multi-agent orchestration, I like solving complex problems with well-structured, modern tooling.

Let’s connect!
