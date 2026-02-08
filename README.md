<div align="center">

# 🛡️ BFG

**Automated web vulnerability discovery from reconnaissance to bug bounty report**

![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Llama](https://img.shields.io/badge/Llama_3.1-0467DF?style=for-the-badge&logo=meta&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

<br>

<img src="https://img.shields.io/badge/status-active_development-brightgreen?style=flat-square" />
<img src="https://img.shields.io/badge/license-proprietary-red?style=flat-square" />
<img src="https://img.shields.io/badge/models-LLM_+_ML_ensemble-blueviolet?style=flat-square" />

</div>

---

## 🔍 Overview

An end-to-end automated security testing system that discovers vulnerabilities in web applications and produces ready-to-submit bug bounty reports. The system orchestrates multiple fine-tuned large language models and specialized machine learning models across an autonomous multi-agent pipeline — each model handles a distinct phase of the security testing workflow.

## 🏗️ Key Architecture

| | Feature | Description |
|---|---------|-------------|
| 🤖 | **Multi-Agent Pipeline** | Purpose-built agents covering reconnaissance, attack planning, execution, evaluation, template generation, validation, and reporting |
| 🧠 | **Fine-Tuned LLMs** | Llama 3.1 8B models, each specialized for a distinct pipeline stage |
| 📊 | **Ensemble ML Classifiers** | Real-time attack scoring and anomaly detection |
| 🔀 | **Two-Stage Template Generation** | AI reasoning separated from output execution via a Template Intent Specification (TIS) layer, with per-vulnerability-class ML models for schema-compliant output |
| 🗺️ | **Framework Mapping** | Automated mapping to MITRE ATT&CK and OWASP Top 10 |
| ✅ | **Reproducibility Validation** | Nuclei template execution with ML-based false positive filtering |

## 🎯 Vulnerability Coverage

Specialized models for OWASP Top 10 categories:

> 📜 Standard Vulnerability Types 

## 📄 Output

Each confirmed finding produces:

- 🧪 Validated **Nuclei template** for reproducible scanning
- 📝 Complete **bug bounty report** with severity scoring, step-by-step reproduction, and remediation recommendations

## 🛠️ Built With

<div align="center">

| ML & AI | Security | Infrastructure |
|---------|----------|---------------|
| PyTorch | Nuclei | FastAPI |
| Llama 3.1 | MITRE ATT&CK | Docker |
| XGBoost | OWASP Top 10 | ChromaDB |
| LightGBM | Sigma | Python |
| CatBoost |

</div>

---

<div align="center">

🔒 *Full architecture documentation available under NDA.*

**[Contact](#)** · **[LinkedIn](#)**

</div>
