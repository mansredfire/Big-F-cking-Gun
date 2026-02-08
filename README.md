<div align="center">
Multi-Agent AI Security Scanner
Automated web vulnerability discovery from reconnaissance to bug bounty report
</div>

Overview
An end-to-end automated security testing system that discovers vulnerabilities in web applications and produces ready-to-submit bug bounty reports. The system orchestrates multiple fine-tuned large language models and specialized machine learning models across an autonomous multi-agent pipeline — each model handles a distinct phase of the security testing workflow.
Key Architecture

Multi-agent pipeline with purpose-built agents covering reconnaissance, attack planning, execution, evaluation, template generation, validation, and reporting
Fine-tuned LLMs (Llama 3.1 8B) for reasoning-heavy tasks across each pipeline stage
Ensemble ML classifiers for real-time attack scoring and anomaly detection
Two-stage template generation separating AI reasoning from output execution via a Template Intent Specification (TIS) layer, with per-vulnerability-class ML models for schema-compliant output
Automated framework mapping to MITRE ATT&CK and OWASP Top 10
Reproducibility validation through Nuclei template execution and ML-based false positive filtering

Vulnerability Coverage
Specialized models for OWASP Top 10 categories including SQL injection, cross-site scripting, broken access control, SSRF, security misconfiguration, authentication failures, and cryptographic failures.
Output
Each confirmed finding produces a validated Nuclei template, Sigma detection rule, and a complete bug bounty report with severity scoring, step-by-step reproduction, and remediation recommendations.
Built With
Python · PyTorch · Llama 3.1 · XGBoost · LightGBM · CatBoost · ChromaDB · Nuclei · FastAPI · Docker

Full architecture documentation available under NDA.
