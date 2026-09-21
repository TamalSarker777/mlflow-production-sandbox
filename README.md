#  MLOps & LLMOps Learning Lab

A hands-on learning repository documenting my journey into MLOps and LLMOps engineering. This project tracks practical experiments, architectural notes, and reproducible implementations using **MLflow**, **PyTorch**, and modern deployment tools.

> **Goal:** Build strong, production-grade intuition for model lifecycle management—from experiment tracking and model registries to LLM tracing and automated evaluation.

---

##  Learning Roadmap & Milestones

- [ ] **Milestone 1: Environment & Tooling Setup** (Git hygiene, virtual environments, MLflow tracking server)
- [ ] **Milestone 2: Traditional ML Lifecycle** (PyTorch experiment tracking, metric logging, model artifact registration)
- [ ] **Milestone 3: Model Registry & Staging** (Model versioning, staging-to-production transitions)
- [ ] **Milestone 4: LLMOps Foundations** (Agent tracing, latency/token logging, automated evaluation)
- [ ] **Milestone 5: Containerization & Serving** (Packaging registered models into Docker for inference)

---

##  Repository Structure

```text
├── traditional-ml/          # Classical ML experiments & lifecycle management
│   ├── src/
│   │   ├── train.py         # PyTorch training loop with MLflow tracking
│   │   └── register.py      # Script to register best runs to MLflow Model Registry
│   └── config.yaml          # Hyperparameters and experiment configurations
│
└── llmops/                  # LLMOps experiments & agent evaluation
    ├── src/
    │   ├── agent.py         # LLM pipeline with MLflow Tracing enabled
    │   └── evaluate_llm.py  # Benchmarking evaluation runs
    └── prompts/             # Prompt engineering templates
