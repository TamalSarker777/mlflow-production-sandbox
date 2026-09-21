# MLOps & LLMOps Lifecycle Sandbox

A production-style sandbox implementing model tracking, evaluation, packaging, and deployment workflows across both classical machine learning and large language model (LLM) architectures using **MLflow**.

---

## 🏗️ Architecture Overview

```text
├── traditional-ml/          # Classical ML: Training, Experiment Tracking & Model Registry
│   ├── src/
│   │   ├── train.py         # Modular PyTorch/scikit-learn training script
│   │   └── register.py      # Promotion to MLflow Model Registry
│   └── config.yaml          # Hyperparameters & data paths
│
└── llmops/                  # LLMOps: Agents, Tracing & Evaluation
    ├── src/
    │   ├── agent.py         # LLM pipeline with MLflow Tracing enabled
    │   └── evaluate_llm.py  # Automated evaluation suite (Faithfulness, Relevance)
    └── prompts/             # Prompt engineering templates