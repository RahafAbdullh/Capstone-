# Capstone# 🔐 Integrating Large Language Models into Cybersecurity Incident Response

**Capstone Project - 2025**  
Bachelor's in Cybersecurity  

Accepted by the National Cybersecurity Authority (NCA) – RDI Grant Initiative

---

## 📌 Project Overview

This project presents a novel approach to enhancing cybersecurity incident response using Large Language Models (LLMs). It integrates two fine-tuned models—**Qwen1.5-7B** and **Primus (LLaMA-3.1-8B)**—into a unified system designed to detect, analyze, and respond to cybersecurity threats with high accuracy and speed.

Built upon the **SEVENLLM framework**, the system leverages deep learning, Retrieval-Augmented Generation (RAG), and multi-agent collaboration through CrewAI to simulate and handle real-world incident scenarios.

---

## 🚀 Key Features

- 🔍 **Qwen1.5-7B**: Fast and structured triage of security incidents
- 🧠 **Primus**: Deep root-cause analysis and response planning
- 🧩 **CrewAI Integration**: Simulated human-agent workflows for realistic response
- 🧾 **RAG Module**: Adds contextual knowledge to model responses
- 🧪 **Tested on Real-World Scenario**: Twitter 2020 Hack Case Study

---

## 🧠 Technologies & Frameworks

- `Python`
- `Hugging Face Transformers`
- `Qwen1.5-7B` (Fine-tuned)
- `LLaMA-3.1-8B` via Primus
- `SEVENLLM` Datasets (Instruct + Bench)
- `CrewAI` for multi-agent simulation
- `RAG (Retrieval-Augmented Generation)`
- `Jupyter Notebook`, `PyTorch`, `CUDA`
- `Docker` (for environment consistency)

---

## 🧪 Evaluation Results

| Metric      | Qwen Model | Primus Model |
|-------------|------------|--------------|
| Accuracy    | XX%        | XX%          |
| F1 Score    | XX%        | XX%          |
| Perplexity  | XX         | XX           |
| BLEU Score  | XX         | XX           |

*(Replace XX with actual results from your evaluation notebook)*

---

## 🧾 Example Case Study: Twitter 2020 Hack

- 🕵️‍♂️ **Qwen Model Output**:  
  Identified spear-phishing via email spoofing and recommended account lockouts and MFA.
  
- 🧠 **Primus Model Output**:  
  Explained social engineering vector, organizational vulnerabilities, and proposed holistic responses like awareness training and internal audits.

---

## 📁 Project Structure
📦 cybersec-llm-response/
┣ models/
┣ data/
┣ scripts/
┣ crewai_simulation/
┣ rag_module/
┣ notebook/
┣ results/
┣ docs/
┣ README.md
┣ requirements.txt
┗ LICENSE

